The Aperture device expands or compacts every single feature on the terrain, similar to bokehÂ in a camera.

## Properties

- **Method**: Choose whether to expand or compact the visuals on the terrain.
    - *Compact:*
    - *Expand:*
- **Iterations**: Number of aperture passes to perform on the terrain. Higher number of passes create pronounced effect at the expense of speed.
- **Kernel**: The Kernel is the shape of the aperture. Changing the kernel can change how the features on the terrain are modified.
    - *Disk:* Large, circular formation.
    - *Diamond* - Small, diagonal squares.
    - *Cross*: Small cross pattern. Can create predictable shape, use with masking for best results.
    - *Octagon*: Large, octagonal formation.
    - *Rectangle*: Large, diagonal squares.
    - *Ring*: Small, circular formation with steps/terraces.
    - *Sobel*: Rectangular stretches which retain corner shapes.
- **Randomized**: Description

[!TIP]
To rotate the direction of the aperture kernels, use the Rotator device before and after the Aperture device to change the direction, and then change it back. See Aperture.tmd example file for a demonstration of this technique.
[TIP!]
