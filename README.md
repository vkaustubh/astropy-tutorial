# The Astropy Tutorial
## by Kaustubh Vaghmare

This repository contains the notebook(s) used by me for teaching the fundamentals of Astropy. It contains

- Jupyter notebooks with code and theory
- And also the data needed to go through some of the code examples.

## What you need?

You can either choose to work with a vanilla Python environment or with the Anaconda distribution.

If you are working with a full Anaconda distribution, Astropy package should already be installed. You can confirm this by running a Python shell and executing the following commands.

    >>> import astropy
    >>> print(astropy.__version__)
    4.0.1.post1

And if you are working with a non-Conda environment, you can install it with ease. As a good practice, we always start with a Virtual environment dedicated to our specific project or work session. For creating the Virtual Environment, choose a directory.

    python3 -m venv astropy_venv
    source astropy_venv/bin/activate

And then install the packages by saying,

    pip install astropy

It is a good option to install some other packages as well which we will need that are not exactly needed for Astropy to work bu t we will need them.

    pip install scipy pandas matplotlib seaborn jupyter jupyterlab

## Starting Off

Ensure whatever environment you are working in, is activated and then start Jupyter Lab.

    jupyter lab
