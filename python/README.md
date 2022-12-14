<div align="center">
  <a href="https://www.python.org/"><img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="64" height="64"></a>
</div>

## Table of Contents

- [Style Guide](#book-style-guide)
- [Virtual Environment & Requirements](#virtual-environment--requirements)

## :book: Documentation

Style Guide: https://peps.python.org/pep-0008/
Special Methods: https://docs.python.org/3/reference/datamodel.html#special-method-names

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

### List local packages

```shell
pip list --local
pip list --local --outdated
pip list --local --uptodate
```
