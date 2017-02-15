World Machine 3.0 introduces a new River system that lets you create beautiful winding rivers. RiverErosion further enhances your river creation by providing a different method of eroding rocky river banks, and even underwater areas. While Hydro uses partially randomized, churning forces to erode the terrain, RiverErosion concentrates on following the flow and creating patterns based on how water flows over and around obstacles.

## Properties

- **Amount**: The amount of erosion. Higher values cause larger, smoother shapes and decay fine details. Lower values preserve details but create slightly rougher curves.
- **Force**: DESCRIPTION
- **Detailed**: Use this option for very high resolution renders where details are very important. The High Quality version requires up to 6x more memory and time to process, but the additional time cost can be worth it for meticulous visuals.

[!TIP]
A great way to create a river environment is to use RiverErosion on a blurred mask from the River, and then apply Hydro erosion to the bottom half of the mask. A practical example of this can be found in "River + RiverErosion + Hydro.tmd" in the GeoGlyph Examples.
[TIP!]