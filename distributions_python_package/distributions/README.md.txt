# distributions package

__distributions__ is a Python module for statistics and data analysis built on top of math and matplotlib libraries and is distributed under the MIT license.
The project was started The project was started in 2022 by Ahmed Limem as a AWS AI & ML scholarship program, it is currently maintained by himself.

# Files

  * Generaldistribution.py:  
    Distribution (class) Generic distribution class for calculating and visualizing a probability distribution.
  * Gaussiandistribution.py:
    Gaussian (class) Gaussian distribution class for calculating and visualizing a Gaussian distribution.
  * Binomialdistribution.py:
    Binomial (class) Binomial distribution class for calculating and visualizing a Binomial distribution.

# Installation
## Dependencies
__distributions__ requires:
  * Python (>= 3.8)
  * Matplotlib (>= 3.1.2)

## User installation
it's better to test this package usin Python virtuel environments, for `win10`, use these commands in `PowerShell`:
```
python -m venv venv_distributions
venv_distributions\Scripts\Activate.ps1
cd python_package
pip install .
```
If you already have a working installation of python and Mathplotlip, the easiest way to install __distributions__ is using `pip`:
```
pip install -U distributions
```

## Testing
After installation, you can launch the test suite from outside the source directory (you will need to have `unittest` installed):
```
python -m unittest test
```
> Random numbers files are given for testing

##Source code
You can check the latest sources with the command:
```
git clone https://github.com/AhmedLimem/Python-Package-for-Gaussian-and-Binomial-Distributions.git
```

## Important links
Issue tracker: https://github.com/AhmedLimem/Python-Package-for-Gaussian-and-Binomial-Distributions/issues