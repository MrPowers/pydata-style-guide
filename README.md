# PyData Style Guide

This document summarizes the best practices when using and writing about popular PyData technologies.

Automated code formatters and code style enforcers obviate the the need for style guides that specify rules for quotation marks and whitespacing.  This document focuses on how to how to use the automated technologies and stylistic guidance that's not yet automated.

## Capitalization

* pandas should always be lowercase
* Dask should always be uppercase
* Conda should be uppercase at the start of a sentence and lowercase otherwise
* Miniconda should always be uppercase
* NumPy instead of Numpy
* DataFrame (note the captial “D” and “F”)
* scikit-learn should be lowercase
* IPython not ipython

## Dask

### Imports

* `from dask.distributed import Client`

