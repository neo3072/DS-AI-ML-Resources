## Python

**Importing Packages**

```python
import numpy as np
import pandas as pd

import matplotlib
import matplotlib.pyplot as plt
```

**Updating Packages**


## Jupyter

**Configuration**
```python
%matplotlib inline
%pylab inline
```

**CLI**

```shell
jupyter notebook # Launch Jupyter
jupyter notebook --debug
```

## IPython

**CLI**


## Conda/Anaconda

**Environment Management**

```shell
conda info -e # List environments
ls -al ~/anaconda/envs/ # List environments in directory

# Create environment and install packages**
conda create -n <env_name> python=<python_version_number> matplotlib numpy scipy scikit-learn jupyter pandas statsmodels nltk seaborn <additional packages> # E.g., name = py352, python version = 3.5.2

# Delete environment
conda remove -n <env_name> --all

# Activate and deactivate environment
source activate <env_name>
source deactivate <env_name>

# Export environment and load
conda env export > <path/filename.yml>
conda env create -f <path/filename.yml>
```

**Package Management**

```shell
conda list

conda search -f python # List available Python packages

conda update conda 
conda update anaconda
conda update --all

conda update -n <env_name> <package_name(s)>
```

*Specific Packages*
```shell
conda update jupyter
```

## PIP

```shell
pip install -U pip # Update PIP
```

-----

## Versions and Locations

**Python**
```shell
which python
which python3
python --version
```

**Jupyter and IPython**
```shell
which jupyter
which ipython
jupyter kernelspec list
```

**PIP**
```shell
which pip
```

-----

## Important File Locations
- Jupyter
- IPython
- Conda
- Python
- General installation directory (mac): /usr/local/bin
- General framewords directory (mac): /Library/Frameworks

-----

## Installations

- [Grunt](http://gruntjs.com/installing-grunt)

## Linux

**OS Updgrading**
```shell
sudo apt-get update && sudo apt-get upgrade
sudo apt-get update && sudo apt-get dist-upgrade

```



