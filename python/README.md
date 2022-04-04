<div align="center">
  <a href="https://www.python.org/"><img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="64" height="64"></a>
</div>

## Table of Contents

- [Style Guide](#book-style-guide)
- [Virtual Environment & Requirements](#virtual-environment--requirements)

## :book: Style Guide

Further reading: https://peps.python.org/pep-0008/

## Virtual Environment & Requirements

### Set up the venv

```shell
python3 -m venv --upgrade-deps /project_folder/venv
```

### Activate the venv

#### Windows

```shell
venv/Scripts/activate
```

#### Linux/macOS

```shell
source venv/bin/activate
```

### Install the requirements

```shell
pip install -r requirements.txt
```

### Create requirements.txt

This requires [pipreqs](https://pypi.org/project/pipreqs/)

```shell
pipreqs --force
```
