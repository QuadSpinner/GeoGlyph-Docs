HelixGrad is a new gradient generator. It creates a gradient arc or helix, which can serve as the base for slope oriented terrains.

This gradient can be useful for distorting or modifying other noises, such as the Advanced Perlin's shape or distortion guides.

## Properties

- *Start*: The degree at which the Helix arc will begin.
- *End*: The degree at which the Helix arc will end.
- *X/Y*: The position of the center of the gradient.
- *Distortion*: The amount of choppiness to add to the gradient.
- *Blur*: The amount of smoothing to be applied to the output.

[!TIP]
Distortion can be very sensitive. Try using very small values such as 0.001 to get larger shapes, and higher values 

If your distortion looks too abrupt, use a medium or high Blur value to compensate. See GG2-HelixGrad-1.tmd.
[TIP!]