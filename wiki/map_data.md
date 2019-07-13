---
title: Map Data
---
# Map Data
* [Intro](#intro)
* [Data Format](#data-format)
* [Serialization](#serialization)

## Intro

All Rust maps (apart from FacePunch created), are stored in a .map file.

When first joining a server that is running a ProcGen map, Rust will generate the map from the:

### Size (1000-6000)

### Seed (0-9999999999)

### MapType (ProcGen/Barren)

The map is then saved into a .map file, and can be found in the Rust install directory inside the maps folder. The map filename 
will be formatted by the MapType.Size.Seed.map



## Data Format

## Serialization
