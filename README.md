# test_packaging_ja

[![PyPI](https://img.shields.io/pypi/v/test_packaging_ja.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/test_packaging_ja.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/test_packaging_ja)][pypi status]
[![License](https://img.shields.io/pypi/l/test_packaging_ja)][license]

[![Read the documentation at https://test_packaging_ja.readthedocs.io/](https://img.shields.io/readthedocs/test_packaging_ja/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/Janie115/test_packaging_ja/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/Janie115/test_packaging_ja/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/test_packaging_ja/
[read the docs]: https://test_packaging_ja.readthedocs.io/
[tests]: https://github.com/Janie115/test_packaging_ja/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/Janie115/test_packaging_ja
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _test_packaging_ja_ via [pip] from [PyPI]:

```console
$ pip install test_packaging_ja
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [Apache 2.0 license][License],
_test_packaging_ja_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://test_packaging_ja.readthedocs.io/en/latest/usage.html
[License]: https://github.com/Janie115/test_packaging_ja/blob/main/LICENSE
[Contributor Guide]: https://github.com/Janie115/test_packaging_ja/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/Janie115/test_packaging_ja/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_test_packaging_ja
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=singlehtml --jobs=auto --write-all; open _build/html/index.html
```