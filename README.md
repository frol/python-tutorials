# Showcases to dive into Python in an hour

You'll need [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html)
(f.k.a. IPython Notebook until version 3.0) to see all features.

In these demos I focused on Python 3.5, though there should be no problems to
run them on Python 2.7 and 3.4+.


## Download Python Tutorials

There are two options how you can get the tutorials:

### Git Clone (preferred)

```bash
$ git clone https://github.com/frol/python-tutorials.git
$ cd python-tutorials
```

### or download this repository as an archive

```bash
$ mkdir python-tutorials
$ cd python-tutorials
$ wget https://github.com/frol/python-tutorials/archive/master.zip
$ unzip master.zip
```


## Prepare environment

Again, there are two options of how to prepare your environment:

### Classic Python using VirtualEnv (Debian-based Linux instructions)

1. Since most of the Linux distributions already have Python installed, you
    only need to install VirtualEnv:

    ```bash
    $ sudo apt-get install python-virtualenv
    ```
2. Create Python Virtual Environment:

    ```bash
    $ virtualenv ./env/
    ```
3. Activate the environment and install dependencies:

    ```bash
    $ . ./env/bin/activate
    $ pip install -r requirements.txt
    ```

### Anaconda Python distribution (crossplatform)

1. [Install Miniconda](http://conda.pydata.org/miniconda.html) (
    [Anaconda](https://www.continuum.io/downloads) will also work, but it
    includes too many unnecessary packages, which you can install into
    Miniconda if necessary)
2. [Create Conda Environment](http://conda.pydata.org/docs/using/envs.html#create-an-environment)
    with Jupyter Notebook:

    ```bash
    $ conda create -n python-tutorials python notebook
    ```
3. [Activate the environment](http://conda.pydata.org/docs/using/envs.html#change-environments-activate-deactivate):

    ```bash
    $ activate python-tutorials
    ```

    NOTE: You should prepend the above command with `source ` (i.e. `source activate ...`)
    when using sh/Bash (Linux, OS X, and in some cases on Windows).


## Start

```bash
$ jupyter notebook --notebook-dir=./notebooks/
```

## Contents

1. `notebooks/Intro.ipynb`
1. `notebooks/Structures.ipynb`
1. `notebooks/Numpy_and_Pandas.ipynb`
