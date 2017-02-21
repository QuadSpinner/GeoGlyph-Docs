One of the most powerful new offerings in GeoGlyph 2 is GeoColor. This advanced gradient toolkit can create terrain textures from a photograph with a single click.

GeoColor can learn color patterns from a photograph (*Extrapolation*), then allows you to pre- and post-process color gradients generated from the image. A modern gradient editor provides minute control over every aspect of the coloration process, while post-production effects provide realistic scattering and diffusion for the final texture.

[!NOTE]

Terminology:
- **Color Map / Gradient / Color Table** - the linear gradient of colors that is applied to the Texture Mask.
- **Texture Mask** - the grayscale/heightfield input that dictates how and where colors are distributed.
- **Texture Map** - the completed texture map that is the output of the device.

[NOTE!]

## Gradient Editor
The modern gradient editor provides a simple and familiar experience in constructing and modifying gradients. You can add a gradient stop by double-clicking on the desired location. To delete a gradient stop, select it and press `Delete`.

The color palette provides a familiar palette, and can also take HEX values. Please note, all HEX values must be in the ARGB format.

The `Reverse Gradient` and `Randomize Stops` buttons let you quickly process the gradient without modifying any of the other settings.

## Extrapolation Properties
To use the Extrapolation features, you must first load a source image. This can be either a file (.bmp, .jpg, .png, .tga, .tiff, .exr, .gif) or an image in the clipboard. Use either the `Clipboard` button or the `Load Image` button to load the image. 

A preview of the image is shown in the bottom of the Properties tab.


- **Samples**: The number of color samples to acquire from the image. Each sample will be represented as a gradient stop.
- **Rotate**: The amount of rotation for the source color map.
- **Scatter**: Randomly scatter color samples to add jagged variety to the color map.
- **Seed**: The random seed of the extrapolation process.
- **Fuzzy Sampling**: 
- **Matching**: This is used when rotation creates "null" areas in the source color map.
    - *Pattern Matching* - detect the pattern next to the missing area and try to recreate a similar pattern.
    - *Edge Matching* - take the pixels at the edge and repeat them.

## Library
This gradient map library consists of color maps created using [Satellite Maps and real world data](IDE--Color-Production-Tools). Any custom presets you save will show up at the top.

The library color maps are numbered, and have an arrow next to the number to show the complexity, ranging from 1 to 3. User presets always have a circle in front of the name.

Unlike pure gradients, the GeoGlyph color maps are stored as "abstract data". This means, when you load a gradient, it will be treated like an image used for extrapolation. Once you load a gradient, you can go to the Properties tab to change the Extrapolation options. This allows you to use advanced features such a Seed, Rotate, and Scatter to modify a color preset easily. The Samples property lets you choose the complexity of your gradient.

Your own presets can be saved to the library with the `Save Preset` button.


## Process Properties
- **Blur**: Applies a simple blur to the texture mask.
- **Jitter**: Randomly scatters the pixels of the texture mask.
- **Soften**: Applies a softening filter to the finished texture map.
- **Stagger**: Adds a staggering effect to the texture map to create small flat areas.


The following properties are available for both pre- and post-processing. Pre-Process versions are applied to the incoming texture mask, while Post-Process versions are applied to the color map.

- **Clarity**: Increases the edge contrast of all features.
- **Auto Level**: Applies automatic color and contrast leveling.
- **Equalize**: Equalizes the color balance.

For more information about using the GeoColor device, see [Color Production Tools](IDE--Color-Production-Tools).

[!TIP]
Screen clipping tools such as the Snipping Tool, OneNote Screen Clip, or a tool like ShareX can be very useful in cliping a portion of an image and loading it in GeoColor through the `Clipboard` button.
[TIP!]

[!TIP]
If you wish to use the exact gradient colors, increase the number of samples to 256. This will give you full color coverage from the source color map.
[TIP!]

[!TIP]
Sometimes you can create two different GeoColor nodes - one with Stagger and one without and blend them in World Machine for added effect.
[TIP!]

[!NOTE]
A video tutorial of GeoGlyph is forthcoming.
[NOTE!]