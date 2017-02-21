DistanceGen is a unique geometry generator. While it can be used by itself to create canyon-like terrains, it has even more potential when used with filters or used to drive other fractalsm such as the Advanced Perlin.

This generator creates sets of "cells" at three different heights: 0% (Blacks), 50% (Grays), 100% (Whites). The resulting heightfield gives stark drop-offs and strong plateaus.

## Properties

- **Whites / Blacks / Grays**: The number of cells at these height levels. The combined cell count creates the ratio between the three cell "groups".
- **Function**: The distance function used to determine the cell shape. 
    - *Euclidean* - creates sharp, angular cells. 
    - *Manhattan* - creates slightly unnatural multi-angled shapes, which can be quite useful when processed further. 
    - *Shepards* - provides stark peaks and sinkholes. 
    - *Euclidean-Manhattan* - creates a hybrid shape merging both distancing functions equally.
- **Seed**: The random seed of the generator.
- **Curved**: Softens the hard edges of the cells.
- **Thermal**: Applies light thermal erosion to the cells.