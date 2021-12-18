# Automatic add 'None' return type to init

[![pypi](https://img.shields.io/pypi/v/add-return-None-to-init)](https://pypi.org/project/add-return-None-to-init/)
[![python-version](https://img.shields.io/pypi/pyversions/add-return-None-to-init)](https://pypi.org/project/add-return-None-to-init/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![License](https://img.shields.io/github/license/soraxas/py-return-None-for-__init__.svg)](https://github.com/soraxas/py-return-None-for-__init__/blob/master/LICENSE)

This moduel automatically adds `None` return type to every init function, i.e.
```py
def __init__(...) -> None:
```

## Usage

``sh
usage: py-add-return-None-to-all-init [-h] [-d] PATH
```

You can run the module with
```sh
py-add-return-None-to-all-init MY_PYTHON_PROJ [--dry-run]
```
With the `--dry-run` flag it will only be verbose on what it's gonna perform without writing to disk. It will performs the actual run it the dry run flag is not presence.

