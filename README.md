# BSQ

# Compilation

Via Makefile

```bash
./102architect
```
# Description

make geometric transformations (rotation to change point of view, translation to move an object, scaling to zoom in and out, reflection
and any combination of these transformations for a point (with matrix)

# Usage
```bash
x abscissa of the original point
y ordinate of the original point

transfo arg1 [arg2]
-t i j translation along vector (i, j)
-z m n scaling by factors m (x-axis) and n (y-axis)
-r d rotation centered O by a d degree angle
-s d reflection over the axis passing through O with an inclination angle of d degrees
```
