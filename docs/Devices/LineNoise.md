LineNoise is a geometric generator that creates sets of lines that can be distorted and used with other noises and fractals for creating layered ridges.

## Properties

- **Type**: Each of the five noise types provide different line patterns.
	- *Random:* Lines with random heights.
	- *Gaussian:* Lines with heights calculated by Gaussian formula. Less variation than random.
	- *Poisson:* Similar to Gaussian but with more variation strength.
	- *Impulse:* Sharp and fewer lines, but with expanded widths.
	- *Uniform:* Uniform lines, with very little variation. Great for creating grooves.
- **Clamped**: Clamps the height of the lines.
- **Eroded**: Applies light thermal erosion to the lines.
- **Seed**: Random seed of the generator.

[!TIP]
LineNoise is rarely used by itself. Most of the time you want to distort it either directly or by passing it to an Advanced Perlin. 

It can also be subtracted from other noises by using a Combiner to create interesting grooves.
[TIP!]
