# Useful functions for/by Sven Buder

## Installation

First installation in command line:
```console
user@computer:~$ python -m pip install --index-url https://test.pypi.org/simple/ --no-deps buder_functions
```

Upgrading to latest version in command line:
```console
user@computer:~$ python -m pip install --index-url https://test.pypi.org/simple/ --no-deps buder_functions --upgrade
```

## buder_plotting.py

buder_plotting.hist2d_bin_colored(X,Y,Z) creates a 2-dimensional histogram (with X and Y as input) with bins colored by Z.

This package was created following the tutorial on https://packaging.python.org/en/latest/tutorials/packaging-projects/
