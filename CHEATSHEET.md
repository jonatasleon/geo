# Cheatsheet

This document contains a list of useful commands to me.

## Conda

[Conda](https://conda.io/docs/) is a package, dependency and environment management system for any language, including Python.

- Activate Conda on Windows (using `cmd.exe`):

```
C:\Users\Will\Anaconda3\Scripts\activate.bat C:\Users\Will\Anaconda3
```

- List environments:

```
conda info --envs
```

- Create a new environment:

```
conda create --name geo python=3.7
```

- Activate an environment and deactivate it:

```
conda activate geo
conda deactivate
```

## JupyterLab

In order to get [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) up and running in a Conda environment, I had to [install a kernel](https://jupyter.readthedocs.io/en/latest/install-kernel.html) - the [IPython kernel](https://ipython.readthedocs.io/en/latest/install/kernel_install.html#kernels-for-different-environments) - in the desired environment:

```
python -m ipykernel install --user --name geo --display-name "Python 3.7 (geo)"
```