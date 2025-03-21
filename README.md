# explaining-models

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/perellonieto/explaining-models/master)


## Python Development

It is recommended to create a virtual environment to install all the
dependencies and run the experiments with the same versions that it was
intended during development. One way to create a virtual environment and load
it is with the following commands


```
python3.10 -m venv venv
source venv/bin/activate
pip install --upgrade pip
```

This creates a virtual environment with Python version 3.10, loads the
environment and upgrades the `pip` package to its latest version.

## Requirements:

All the requirements are listed in the `requirements.txt` file. Those can be
automatically installed in the virtual environment with

```
# Ensure that the virtual environment has been loaded
source venv/bin/activate 
pip install -r requirements
```

## Jupyter Notebook

Use Jupyter Notebook to visualise and edit the experiment files.

```
pip install jupyter
jupyter notebook
```
