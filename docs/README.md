A5 Project Documentation
========================

Build documentation for A5 Project.

## Prerequisites

Conda 23.7.4

## Documentation

Create a Python environment with a set Python version.

```shell
$ conda create --name sphinx_venv python=3.11
```

Activate the environment.

```shell
$ conda activate sphinx_venv
```

Install Python packages.

```shell
(sphinx_venv) $ pip install sphinx
```

Check if sphinx is installed.

```shell
(sphinx_venv) $ sphinx-build --version
```

Build the documentation.

```shell
(sphinx_venv) $ sphinx-build -M html docs/source/ docs/build/
```

Open docs/build/html/index.html in the browser.

Testing code.

```shell
(sphinx_venv) $ make doctest
```

Deactivate the environment.

```shell
(sphinx_venv) $ conda deactivate
```
