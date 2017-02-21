This device quantizes the heightfield into discrete cells as defined by the Distance function. The default Euclidian function creates basalt pillar-like shapes.

## Properties

- **Scale**: The relative size of the cellular subdivision.
- **Chaos**: The general randomness of the subdivision. Low values create systematic cells; high values cause the cells to widely differ both in shape and number of sides.
- **Seed**: The random seed for the generation process.
- **Function**: The distance function used to determine the cell shape. *Euclidean* creates sharp, angular cells. *Manhattan* creates slightly unnatural multi-angled shapes, which can be quite useful when processed further. *Shepards* provides stark peaks and sinkholes. *Euclidean-Manhattan* creates a hybrid shape merging both distancing functions equally.
