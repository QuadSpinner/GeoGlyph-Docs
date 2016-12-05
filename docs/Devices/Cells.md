This device quantizes the heightfield into discrete cells as defined by the Distance function. The default Euclidian function creates basalt pillar like shapes.

## Properties

- **Scale**: The relative size of the cellular subdivision.
- **Chaos**: The general randomness of the subdivision. Lower values create systematic cells while higher values cause the cells to differ widely in both shape and number of sides.
- **Seed**: The random seed for the generation process.
- **Function**: The distance function used to determine the cell shape. *Euclidean* creates sharp, angular cells. *Manhattan* creates slightly unnatural multi-angled shapes, which can be quite useful when processed further. *Shepards* provides stark peaks and sinkholes. *Euclidean-Manhattan* creates a hybrid shape merging both distancing functions equally.
