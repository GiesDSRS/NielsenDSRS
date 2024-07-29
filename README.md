# Nielsen Retail Reader


| | |
| --- | --- |
| License | [![License](https://img.shields.io/badge/LICENSE-blue)](https://github.com/pratikrelekar/NielsenDSRS/blob/main/LICENSE) |
| Dependencies | [![Dask Latest Release](https://img.shields.io/badge/Dask-orange)](https://www.dask.org) \| [![Distributed](https://img.shields.io/badge/distributed-yellow)](https://distributed.dask.org) \| [![Numpy](https://img.shields.io/badge/numpy-green)](https://numpy.org) \| [![toolz](https://img.shields.io/badge/toolz-red)](https://github.com/pytoolz/toolz)\|




## Overview:

**Nielsen Retail Reader’s** is a special-purpose library and it's main purpose is to facilitate ease of processing of Nielsen Retail Scanner data of Kilt’s Center’s Nielsen IQ data used for Academic research only. The striking feature of this library is Dask which acts as an underlying framework that uniquely empowers the user to read Nielsen data with limited on device resources (by processing larger-than-memory data in chunks and distributed fashion). It understands the Kilts/Nielsen directory structure.

## IMPORTANT:

### Access to Nielsen Retail Data:

Please note that Nielsen retail data is proprietary and access is restricted to individuals whose institutions have an existing subscription or agreement with Nielsen. If you intend to use this library for accessing and analyzing Nielsen data, you must first ensure that you are authorized to do so by your institution. Unauthorized access or use of this data may violate terms of use and could have legal implications. Nielsen dataset should strictly follow standard naming convention as per laid out by Nielsen and Kilts Center of Marketing and under no circumstances the naming convention should be changed.

**NielsenRetail** processes Retail Scanner Data.

## Table of Contents

- [Main Features](#main-features)
- [Where to get it](#where-to-get-it)
- [Dependencies](#dependencies)
- [License](#license)
- [Documentation](#documentation)
- [Background](#background)
- [Getting Help](#getting-help)
- [Discussion and Development](#discussion-and-development)

## Main Features
Here are just a few of the things that NielsenRetail does well:
  - Efficiently manages Nielsen directory and hierarchy, simplifying the process for researchers and significantly reducing the time needed to navigate through Nielsen documentation.
  - Size mutability: Processes dataframes [**larger-than-memory**](https://examples.dask.org/dataframe.html) on a single machine through batch processing.
  - Distributed computing for terabyte sized datasets enhancing the overall data reading speed by utlising [**low-latency**](https://distributed.dask.org/en/stable/efficiency.html) feature of Dask.
  - Provides simple yet distinct commands for separating sales, stores, and products data for analysis purposes.
  - This package has excellent compatibility with [**Numpy**](https://numpy.org), [**Pandas**](https://pandas.pydata.org), [**Scikit-learn**](https://scikit-learn.org/stable/), [**SQL databases** like Postgres](https://www.postgresql.org) etc.


## Where to get it
The source code is currently hosted on GitHub at:
https://github.com/pratikrelekar/NielsenDSRS

Binary installers will be available at [Python Package Index (PyPI)](https://pypi.org/)

For pip install:
```sh
# or PyPI
pip install git+https://github.com/pratikrelekar/NielsenDSRS
```
