Derived from and augmenting World Machine's Select Height device, HeightFrag adds fragmentation capabilities. The output heightfield is more than a mere horizontal slice of the input terrain. It creates fragmented patches that surpass the confinement limits to generate unique shapes. Elaborate textures can also be made when running the output through the Colorizer device. Additionally, HeightFrag can supplement randomized elements to the heightfield by passing it back to the terrain through a Combiner. GeoGlyph's Sandstone utilizes a specialized version of HeightFrag to produce that exquisite color output. 

## Properties

### Altitude 
- **Maximum**: The maximum limit within which the processing takes place.
- **Minimum**: The minimum limit within which the processing takes place.
- **Falloff**: Smooths the transition of the effect beyond the limit.
### Fragmentation 
- **Scale**: Scale of the shape fragments
- **Seed**: Random seed.
- **Intensity**: Intensity of the fragmentation
- **Mask**: How much effect the mask has on the processing.
- **Warping**: Warping applied to the fragmentation process




