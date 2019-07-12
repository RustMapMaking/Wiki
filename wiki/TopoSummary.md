---
title: Rust Topologies - Summary 
---

<h3>Rust Topology (summarized)</h3>
<hr>
<p>What is Topology?</p>
<p>Topology is the group of layers that make up the map we walk on in-game. These are divided into 3 groups:</p>
<ul>
   <li>Biome: The underlying layer that makes up the general temperature of the land</li>
   <li>Splat: The visual ground texture layer that you see when painting</li>
   <li>Topology: The invisible layer that controls what spawns in that painted area</li>
</ul>
<p>Below you will find what topologies do what in-game.  Allowed Topologies are the only topologies that will cause these items to spawn. Green #s will reference Allowed topologies and red #s will reference the blocking topologies.</p>
<table>
<thead>
<tr>
   <td>&nbsp;</td>
   <td colspan="4">BIOMES</td>
   <td colspan="8">SPLAT</td>
   <td>TOPOLOGY</td>
   </tr>
<tr class="header">
   <th></th>
   <th>Arid</th>
   <th>Temp</th>
   <th>Tundra</th>
   <th>Arctic</th>
   <th>Dirt</th>
   <th>Snow</th>
    <th>Sand</th>
   <th>Rock</th>
   <th>Grass</th>
   <th>Forest</th>
   <th>Stones</th>
   <th>Gravel</th>
   <th><span style="color:green">Allowed</span>/<span style="color:red">Blocked</span></th>
</tr>
</thead>
<tbody>
 <tr >
  <td>Collectable-CORN</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Riverside,Lakeside<span style="color:green;font-size: large; font-family: 'Wingdings 2'">&#117;&#118;</span><span style="color:red;font-size: large;font-family: 'Wingdings 2'">&#120;&#123;&#124;&#125;</span><img src="wiki/images/11.png"></td>
 </tr>
<tr >
  <td>Collectable-STONE</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Forest</td>
 </tr>
 <tr >
  <td>Collectable-HEMP</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field,Forest</td>
 </tr>
 <tr >
  <td >Collectable-WOOD</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Cliff, Beachside,<br>Forestside, Forest, Oceanside,<br>Riverside, Lakeside, Cliffside</td>
 </tr>
 <tr>
 <td>Collectable-MUSHROOM</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Forest</td>
  
 </tr>
 <tr >
  <td>Collectable-PUMPKIN</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Riverside, Lakeside</td>
 </tr>
 <tr >
  <td>LOOT</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">Monument</td>
 </tr>
<tr >
  <td>ORES</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">Decor, Cliffside, Clutter</td>
 </tr>
 <tr >
  <td>Temp Forest</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Forest, Decor, Cliffside<br>Clutter</td>
 </tr>
 <tr >
  <td>Temp Forest Sm</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Forest, Decor, Cliffside<br>Clutter</td>
 </tr>
<tr >
  <td>Tundra Forest</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
 <td markdown="span">Forest, Decor, Cliffside<br>Clutter</td> 
 </tr>
 <tr >
  <td>Tundra Forest Sm</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
 <td markdown="span">Forest, Decor, Cliffside<br>Clutter</td>
 </tr>
<tr >
  <td>Arctic Forest</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Cliffside</td>
 </tr>
 <tr >
  <td>Arctic Forest Snow</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Forest</td>
  
 </tr>
 <tr >
  <td>Arid Palms Dense</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Beachside, River<br>Riverside, Lake, Lakeside</td>
 </tr>
 <tr >
  <td>Arid Palms Light</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Beachside, River<br>Riverside, Lake, Lakeside</td>
 
 </tr>
<tr>
 <td>Arid Palms SuperDense</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
   <td markdown="span">Beachside, Forest, Lakeside, Cliffside</td>
 </tr>
<tr>
 <td>Arid Cactus</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field</td>
  
 </tr>
<tr>
 <td>Junkpiles</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
   <td markdown="span">Roadside, Powerline</td>
 </tr>
<tr>
 <td>Junkpiles Water</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">Offshore</td>
  
 </tr>
<tr>
 <td>Driftwood</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">Beach</td>
 
 </tr>
<tr>
 <td>LOGS Dry</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">Forest, Forestside</td>
 </tr>
<tr>
 <td>LOGS Snow</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
   <td markdown="span">Forest, Forestside</td>
 
 </tr>
<tr>
 <td>LOGS Wet</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
    <td markdown="span">Forest, Forestside</td>
  
 </tr>
<tr>
 <td>Temp Beachforest Sm</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Beachside, Riverside, Lakeside</td>
 </tr>
<tr>
 <td>Temp Field Sm</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Cliffside</td>
  </tr>
<tr>
 <td>Temp Field Lg</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Field, Decor, Cliffside, Hilltop</td>
 </tr>
<tr>
 <td>Temp Forest Deciduous</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Forest, Decor, Cliffside, Clutter</td>
 </tr>
 <tr><td>Temp Forest Deciduous Sm</td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">Forest, Decor, Cliffside, Clutter</td>
 </tr>
 <tr>
   <td><b>Unconfirmed</b></td>
  </tr>
 <tr>
<td>Rowboat</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">Beachside, Oceanside</td>
  
 </tr>
 <tr>
<td>RHIB Boat</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">Offshore</td>
  
 </tr>
 <tr><td>Mini-copter</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">Roadside</td>
 
 </tr>
 <tr><td>Hot Air Balloon</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">Field</td>
 
 </tr>
 <tr><td>Drinkable Water</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">River, Lake</td>
 </tr>
 <tr><td>Animals</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">Mainland</td>
 </tr>
 <tr><td>Iceburgs</td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span"></td>
  <td markdown="span">:heavy_check_mark:</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">&nbsp;</td>
  <td markdown="span">Ocean, Offshore</td>
 </tr>

</tbody>
</table>
