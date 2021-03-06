# jupyter-publication-scripts

Useful scripts for Making publication ready Python Notebooks

This repository is intended to provide a discussion and development platform
for using Jupyter Notebooks in scientific workflows as described in
http://blog.juliusschulz.de/blog/ultimate-ipython-notebook.

## Installation

Run ```python setup.py install``` to install the extension. In order to install into
the user directory add ```--user``` option.

To activate the preprocessors in your configuration file, run ```python -m
jupyterpublicationscripts``` (to deactivate add ```--decativate```).

## Usage

You can use the package as usual, e.g. ```from publicationextensions import PrettyTable```

## Tutorial

A tutorial on how to use the exensions provided in this repository is available in [here](../master/tutorial/tutorial.md).

We also provide an [example notebook](../master/example/ExampleNotebook.ipynb) demonstrating all the features that come with this repository. (Although github can render notebooks, since the interesting features are added with this repository and other extensions, they are not properly displayed.)
