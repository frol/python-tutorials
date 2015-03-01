# Showcases to dive into Python in an hour

You'll need Jupyter (which was known as IPython Notebook until version 3.0) to
see all features.

In these demos I focused on Python 2.7, though there should be no problems to
run them on Python 3.4+.

## Prepare environment

```bash
$ sudo apt-get install python-virtualenv
$ virtualenv ./env/
$ . ./env/bin/activate
$ pip install ipython[notebook]
```

Clone

```bash
$ git clone https://github.com/frol/python-tutorials.git
$ cd python-tutorials
```

or download this repository:

```bash
$ mkdir python-tutorials
$ cd python-tutorials
$ wget https://github.com/frol/python-tutorials/archive/master.zip
$ unzip master.zip
```

## Start

```bash
$ ipython notebook --notebook-dir=./notebooks/
```

## Contents

1. `notebooks/Intro.ipynb`
1. `notebooks/Structures.ipynb`
1. `notebooks/Numpy_and_Pandas.ipynb`


