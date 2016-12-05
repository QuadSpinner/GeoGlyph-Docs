# Perturb
##### Device :: Effect

> This device creates perturbations across the terrain, mimicking swirling water. This can be a very useful effect for creating complex rock formations and desert scenes. When eroded, perturbed terrains can create very believable multi-level mountains.

## Properties

> - **Subdivision**: The intensity of perturbation force. Low values create larger shapes with calm swirls, while high values create smaller shapes with more chaos.
> - **Iterations**: The number of perturb iterations to perform. Each iteration creates additional steps/terraces.

### Warning
> This device generates hard edges which can cause erosion spikes. Use Denoise or KillSpike on the eroded terrain, or use Thermal Erosion before eroding.