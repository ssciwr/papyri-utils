# Welcome to papyri-utils

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ssciwr/papyri-utils/ci.yml?branch=main)](https://github.com/ssciwr/papyri-utils/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/ssciwr/papyri-utils/branch/main/graph/badge.svg)](https://codecov.io/gh/ssciwr/papyri-utils)

A utility Python package with code that is required by both the RAG framework [papyri-assistant](https://github.com/ssciwr/papyri-assistant) and the project for data harvesting and database ingestion [scrapyrus](https://github.com/ssciwr/scrapyrus).

## Installation

The Python package `papyri_utils` can be installed from PyPI:

```
python -m pip install papyri_utils
```

## Development installation

If you want to contribute to the development of `papyri_utils`, we recommend
the following editable installation from this repository:

```
git clone git@github.com:ssciwr/papyri-utils.git
cd papyri-utils
python -m pip install --editable .[tests]
```

Having done so, the test suite can be run using `pytest`:

```
python -m pytest
```

## Acknowledgments

This repository was set up using the [SSC Cookiecutter for Python Packages](https://github.com/ssciwr/cookiecutter-python-package).
