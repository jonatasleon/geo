# Cheatsheet

This document contains a list of useful commands to me.

## Conda

[Conda](https://conda.io/docs/) is a package, dependency and environment management system for any language, including Python.

- Activate Conda on Windows (using ```cmd.exe```):

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

- Activate or deactivate an environment:

```
conda activate geo
conda deactivate
```