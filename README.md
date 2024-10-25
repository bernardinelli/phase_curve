
This is a lightweight and bare bones implementation of the commonly used asteroid phase curve models, with an associated simple chi2 fitter using scipy least squares. This was developed as part of the production of the [LSST DP0.3](https://dp0-3.lsst.io/index.html) and has been used as an independent verification of the package [Sorcha](https://github.com/dirac-institute/sorcha) (which uses the excellent [sbpy](https://sbpy.org/) under the hood).

The only dependencies are `numpy` and `scipy`, see code and/or docstrings for usage details. 

# Installation
Usual installation with pip:
```
pip install phase_curve
```
