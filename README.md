# ms2
> **m**icro**s**ervice **m**edia **s**erver

ms2 is a microservice-based home media server written in Python. It aims to capture the functionality of home media solutions like Plex while remaining simple and lean.

# Installation
At the moment, the only installation option is with pip.
<!--
Either opt for [install via package](#installation-via-package) or [install via pip](#installation-via-pip). If you're not sure which to use, go with the pip install.

## Installation via package
Currently no package builds are available, and [installation via pip](#installation-via-pip) is the only option.


## Installation via pip
-->
Ensure you have Python 3.5+ and pip:

```bash
$ python --version         # Might be `python3` on your distro.
Python 3.8.2               # Must be >3.5!
$ python -m pip --version
pip 20.0.2 from /usr/lib/python3.8/site-packages/pip (python 3.8)
```
<!-- Will uncomment when PyPI builds are available.
Install from PyPI:

```bash
$ python -m pip install ms2
```
-->

If you want to download the source from GitHub and install that, you can do that instead:
```bash
$ git clone https://github.com/ingrinder/ms2
$ cd ms2/
$ python -m pip install .
```


# Project Structure
| File/Directory     | Description            |
|:-------------------|:-----------------------|
| `ms2/`             | Source code            |
| `test/`            | Unit tests             |
| `doc/`             | Documentation          |
| `LICENSE`          | Copy of GNU GPLv3      |
| `requirements.txt` | pip requirements file  |
| `setup.py`         | pip packaging file     |



# Developer info
## Tests
ms2 is developed using a test-driven mindset. Unit-tests are available to run as follows:
```bash
$ python -m unittest
```
Alternatively:
```bash
$ python setup.py -q test
```

<!-- Will write contribution guidelines later.
# Contribution
Contribution guidelines are detailed elsewhere.
-->
