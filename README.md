# Demo Package

## Goal

This is a Pig Latin converter that demonstrates the basic structure of a Python package.

<local change>
## Installation

### For regular users

If you just want to use this project, you can simply install it with:

```shell
python -m pip install git+https://github.com/<username>/pig-latin
```

This will install the package and all of its dependencies into your current Anaconda
environment.

### For developers

If you want to help develop this project, please follow the following steps to get
started.

First clone the repository from GitHub to your personal folder on Workbench:

```shell
git clone https://github.com/<username>/pig-latin
```

Finally, install the package and its dependencies using pip:

```shell
python -m pip install -e .[dev]
```

## Usage

To use the package, simply start a Python interpreter and import the package like so:

```python
>>> from pig_latin.latin import pig_latin
>>> pig_latin("Hello World!")
```

## Contributing

If you want to contribute to this project, feel free to clone the code, make
improvements and open a pull request!

If you have suggestions or remarks not directly related to the project's code or
documentation, feel free to e-mail the authors.

## Maintainers

This project is maintained by:

1. <username> (<e-mail>)
