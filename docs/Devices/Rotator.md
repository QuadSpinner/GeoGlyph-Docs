# Rotator
##### Device :: Utility

> The Rotator device lets you rotate a heightfield at any point in the graph. This is useful for many operations.

#### Properties
- **Degrees**: The amount by which the heightfield is rotated. The range is 0 to 360 degrees.

#### Additional Information
> Rotator works in a similar fashion as World Machine 3's Rotate Distortion input. However, unlike the distortion input, the Rotator device can be implemented at any point in your graph as it is a post-process effect.

Rotator works in its own localspace. Even when you are working in world space, the Rotator device can only read what is in the current render extents. It will mirror edge pixels when it encounters empty areas outside of the extents which become visible at odd angles.
> **Usage Tip**
> To get non-perpendicular results from a filter, try rotating the input (for example, to an Erosion node) by 45 degrees. Then rotate the processed output (from the Erosion device) by -45 degrees to bring it back to the original heading.

##### Does not tile