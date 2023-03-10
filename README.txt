# linmapper 0.0.9
#### Developed by Supratim Das
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?)

## Package Description
linmapper is a Python package that allows users to transform vertices of complex numbers from one plane (Z) to another plane (f(Z)). The package includes a function called linmapper(Z, fZ) that takes in two sets of arrays of complex numbers representing vertices of Z-plane and f(Z)-plane, and returns the function f(Z) that transforms the vertices from Z-plane to f(Z)-plane.


## Installation
To install linmapper, simply use pip:

```python
pip install linmapper
pip install numpy
```

## Usage
To use the linmapper() function, first import the package:

```python
import linmapper as lmp
import numpy as np
```

Then, create two arrays of complex numbers representing the vertices of Z-plane and f(Z)-plane, respectively:

```python
Z = np.array([-1+1j, 1+1j, 1+2j, -1+2j])
fZ = np.array([-2-1j, -2+7j, -6+7j, -6-1j])
```
Finally, call the linmapper() function with these arrays as arguments:


```python
lmp.linmapper(Z, fZ)
```

The function will return a function object that can be used to transform any other complex number from Z-plane to f(Z)-plane.

## Contributing
If you find a bug or have a suggestion for a new feature, please open an issue on GitHub. Pull requests are also welcome!

## License
linmapper is released under the MIT license. See LICENSE for details.