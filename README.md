# Using Python and Jupyter to analyze data

## Getting started

There are a number of ways to [install Jupyter](http://jupyter.readthedocs.io/en/latest/install.html), the most recommended being by using [Anaconda](https://www.continuum.io/downloads). I've never used Anaconda and find it easier to install with [Pip](https://pypi.python.org/pypi/pip) (A package manager for Python, think Python's `npm`,) preferably in a virtual environment. I like to use [Virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/).

```bash
$ mkvirtualenv jupyter-skillshare
(jupyter-skillshare) $
```

The parentheses indicate that you're inside your virtualenv. If you need to exit the environment, you can type `deactivate`. To re-enter the virtual environment, type `workon jupyter-skillshare` (or whatever the name of your environment.)

When you have your virtual env ready, clone the repo:

```bash
(jupyter-skillshare) $ git clone git@github.com:WPMedia/gfx-jupyter-skillshare.git jupyter-skillshare
```

