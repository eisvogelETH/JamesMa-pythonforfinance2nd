# Project Initialization Guide

## Prerequisites

Ensure you have the following installed on your system:

- **Python** >= 3.11 ([Download here](https://www.python.org/downloads/))
- **Poetry** ([Installation Guide](https://python-poetry.org/docs/#installation))

## Setting Up the Project

Follow these steps to initialize the project:

### 1. Install Dependencies

Once Poetry is installed, navigate to your project directory and run:

```sh
poetry install
```

This will install all dependencies listed in `pyproject.toml`.

### 2. Setting Up VSCode Kernel

If you are using **VSCode**, execute the following commands to create a Jupyter Kernel for your Poetry environment:

```sh
poetry shell
python -m ipykernel install --user --name=jamesma --display-name "Python (James Ma)"
```

This will create a Jupyter kernel named **Python (James Ma)**, allowing you to select it as the interpreter in VSCode.

## Verification

To ensure everything is set up correctly, run:

```sh
poetry run python --version
```
You should see the installed Python version as output.
