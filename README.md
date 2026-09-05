# cs2-map-maker-maps

Real-world Cities: Skylines II maps produced by
[cs2-map-maker](https://github.com/chrisagiddings/cs2-map-maker).

Each map lives in its own folder named `{City name} - {short-hash}`, where the hash is
derived from the inputs that define the map (centre, exaggeration, sea level, channel
settings), so two maps with the same name never collide and re-publishing the same
configuration updates the same folder.

```
Chattanooga - a4f662m/
├── README.md                    # height scale, sea level, centre, import steps
├── Chattanooga_heightmap.png    # 4096 x 4096 16-bit playable heightmap (14.336 km)
├── Chattanooga_worldmap.png     # 4096 x 4096 16-bit world map (57.344 km)
├── Chattanooga_qa.png           # QA contact sheet
├── Chattanooga_manifest.json    # full run record
└── resources/                   # 256 x 256 resource masks, when present
```

## Importing a map

1. Copy the `*_heightmap.png` and `*_worldmap.png` into
   `%USERPROFILE%\AppData\LocalLow\Colossal Order\Cities Skylines II\Heightmaps\`.
2. In the CS2 map editor, import the heightmap, then the world map.
3. Set the **height scale** to the value in the map's README (also in the manifest).

## Maps

<!-- maps:start -->
| Map | Centre | Height scale | Sea level | Exag. | Buildable | Relief | QA | Published |
|---|---|---|---|---|---|---|---|---|
| [Chattanooga - 109bf4e](Chattanooga%20-%20109bf4e/) | 35.0456, -85.3097 | **610 m** | 63 m | ×1.00 | 51% | 485 m | [QA](Chattanooga%20-%20109bf4e/Chattanooga_qa.png) | 2026-09-05 |
<!-- maps:end -->
