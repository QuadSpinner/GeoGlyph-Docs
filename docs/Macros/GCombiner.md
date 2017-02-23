GCombiner works exactly like the default Combiner, but it also outputs a mask for the input terrains. This device is excellent for selectively processing either input terrain after combining.GCombiner is also useful for texturing – when you merge sand dunes and mountains, for example. The mask can be hard or soft, with controllable smoothing.

## Properties

### GCombiner

- **Method**:
 	
    - *Average*: Average the two terrains together; the strength parameter controls the weighting of the average.
    - *Add*: Add the 2nd terrain to the 1st. The strength control adjusts the amount of addition.
    - *Subtract*: Subtract the 2nd terrain from the 1st. The strength control adjusts the amount of subtraction.
    - *Multiply*: Multiply the terrains together. The strength control blends from none to full multiplication.
    - *Max*: Use the tallest height of either terrain at each point.
    - *Min*: Use the lowest height of either terrain at each point.
    - *Power*: Exponentiate the 1st terrain with varying power based upon the 2nd.
    - *Root*: Take the root of the 1st terrain with varying power based upon the 2nd.
    - *Detail*: Values in the second heightfield above 0.5 are added to the first; if they're below that, they're subtracted.
    - *Differences*: Returns the differences only between the two heightfields.
    - *Screen*:

- **Strength**:
- **Smoothing**:
- **Invert**:
- **Hard Mask**:
- **Hardness**: