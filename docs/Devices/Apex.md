Apex uses Euclidean distancing (the same function used to create the Voronoi pattern) to take any heightfield and turn it into a stark, pyramid-like mountain chain. It requires a terrain with a large difference between the highest and lowest points.

## Properties

- **Steepness**: The steepness of the mountains that will be formed through distancing.

[!TIP]

Shapes with a hard outline will create better, and more controllable shapes. Try using @Collapse on a noise before applying Apex for better results.

[TIP!]

