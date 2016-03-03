
This is a short tutorial involving writing and training an autoencoder from
scratch on the MNIST dataset using [autograd][]. Part of the [git
book][book] for the PIGlets reading group at the University of Edinburgh.

Installing Requirements
=======================

The requirements file is defined as a [conda][] yml file. The easiest way
to install the environment is to use [miniconda][], and the fastest way to
install miniconda is on a 64 bit Linux system is:

```
curl https://repo.continuum.io/miniconda/Miniconda-latest-Linux-x86_64.sh | bash
```

Once installed, you can then install an environment with this yml file:

```
conda env create -f environment.yml
```

Then, to activate it:

```
source activate autoencoders
```

Starting the Tutorial
=====================

Everything is in the [Jupyter][] notebooks, so start up the Jupyter server
with:

```
jupyter notebook
```

The server will automatically open in your browser (or you'll find it at
`http://localhost:8888`) and you can open the notebook files.

[autograd]: https://github.com/HIPS/autograd
[book]: https://www.gitbook.com/book/piglets/the-piglets-book/details
[conda]: http://conda.pydata.org/docs/
[miniconda]: http://conda.pydata.org/miniconda.html
[jupyter]: http://jupyter.org/
