SlopeNoise is, as the name suggests, a special noise for creating slopes or a single face of a mountain. SlopeNoise is built on a Perlin-like random noise, which is filtered to create curvature platforms with runoffs that facilitate erosion lines.

## Properties

- **Diffuse**: Controls the size of the features. Smaller values give finer, noisier features, while larger values give larger platform-like features.
- **Degrees**: The direction of the slope.
- **Expand**: Controls the expansion of the platform features.
- **Kernel**: The Kernel is the shape of the features. Changing the kernel can change how the features on the terrain are modified.
    - *Cross*: Small cross pattern. Can create predictable shape, use with masking for best results.
    - *Diamond* - Small, diagonal squares.
    - *Octagon*: Large, octagonal formation.
    - *Disk:* Large, circular formation.
    - *Sobel*: Rectangular stretches which retain corner shapes.
- **Seed**: The seed that controls the randomization of the device.

[!TIP]
SlopeNoise can be merged with an Advanced Perlin either by using a Combiner or by using the Shape, Distortion, and Persistence guides in the Advanced Perlin. See GG2-SlopeNoise.tmd example file.
[TIP!]