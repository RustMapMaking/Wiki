---
title: Map Data
---

## Intro

All Rust maps (apart from FacePunch created), are stored in a .map file.

When first joining a server that is running a ProcGen map, Rust will generate the map from the:

### Size (1000-6000) : Seed (0-9999999999) : MapType (ProcGen/Barren)

The map is then saved into a .map file, and can be found in the Rust install directory inside the maps folder. The map filename 
will be named MapType.Size.Seed.map

Custom maps are essentially a pre-generated map, which is downloaded from an URL rather than being generated based on certain values.

## Data Format

Map files are stored in the format below, and compressed using a LZ4Stream.

They first contain the World Serialization number, currently 9 and then the WorldData.

The WorldData is stored in the following format:

``` csharp
public class WorldData
	{
		[ProtoMember(1)] public uint size = 4000; // The size of the Terrain, in Unity metres.
		[ProtoMember(2)] public List<MapData> maps = new List<MapData>();
		[ProtoMember(3)] public List<PrefabData> prefabs = new List<PrefabData>();
		[ProtoMember(4)] public List<PathData> paths = new List<PathData>();
	}
```

The MapData contains a layer (Ground, Biome, Heightmap etc) and the corresponding ByteMap.

It is stored in the following format:

``` csharp
public class MapData
	{
		[ProtoMember(1)] public string name; // ByteMap name (terrain, water, ground, topology etc)
		[ProtoMember(2)] public byte[] data; // The bytemap data.
	}
```

The PrefabData contains info on the ID of the prefab, and it's world space values.

It is stored in the following format:

``` csharp
public class PrefabData
	{
		[ProtoMember(1)] public string category; // Decor, Monument etc
		[ProtoMember(2)] public uint id; // PrefabID
		[ProtoMember(3)] public VectorData position; // Vector3 of the position in world space.
		[ProtoMember(4)] public VectorData rotation; // Vector3 of the rotation in world space.
		[ProtoMember(5)] public VectorData scale; // Vector3 of the scale in world space.
	}
```

The PathData contains info on the Rivers and Roads of the map.

It is stored in the following format:

``` csharp
public class PathData
	{
		[ProtoMember(1)] public string name; // River or Road
		[ProtoMember(2)] public bool spline;
		[ProtoMember(3)] public bool start;
		[ProtoMember(4)] public bool end;
		[ProtoMember(5)] public float width;
		[ProtoMember(6)] public float innerPadding;
		[ProtoMember(7)] public float outerPadding;
		[ProtoMember(8)] public float innerFade;
		[ProtoMember(9)] public float outerFade;
		[ProtoMember(10)] public float randomScale;
		[ProtoMember(11)] public float meshOffset;
		[ProtoMember(12)] public float terrainOffset;
		[ProtoMember(13)] public int splat;
		[ProtoMember(14)] public int topology;
		[ProtoMember(15)] public VectorData[] nodes; // List of the world spaces of the individual nodes.
	}
```
