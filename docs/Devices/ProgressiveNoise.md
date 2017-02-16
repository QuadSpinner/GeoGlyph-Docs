ProgressiveNoise is a surface noise effect, which can be very helpful in breaking up smooth-looking terrains, or adding a bit of grit to the landscape.

## Properties

- **Amount**: The intensity of the noise.
- **Type**: The type of noise to apply.
	- *Random:* Large, random blocks good for creating rocks.
	- *Gaussian:* Lower bump noise with smooth shapes.
	- *Poisson:* Similar to Gaussian but with sharper noise forms between the smoother ones.
	- *Impulse:* Sharp, blocky noise. Useful if you are going to erode or smooth the terrain right after this device.
	- *Laplacian:* Low yield noise, great for creating bumps.

[!TIP]
It is highly recommended that a mask be applied to the device. Applying noise to the entire terrain may create a predictable look. Try using different noise types for different areas and/or altitudes.
[TIP!]