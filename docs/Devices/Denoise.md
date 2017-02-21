Denoise is a general purpose noise removal filter. It systematically cleans up random noise, spikes, and extremely sharp edges.

A single iteration is appropriate in most cases. For extremely noisy terrains that require many passes, it is recommended that the desired area be masked to protect the rest of the terrain from losing important details.

## Properties

- **Iterations**: The number of denoising iterations to perform on the terrain.

[!TIP]

Using Denoise over @KillSpike is recommended, as it uses a better, more powerful algorithm.

[TIP!]


