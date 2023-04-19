# Generate a Project Skeleton with Cookiecutter

## Prerequisites

As a preparation for this tutorial, please install:

* [cookiecutter](https://cookiecutter.readthedocs.io/en/2.1.1/installation.html#install-cookiecutter)
* [Poetry](https://python-poetry.org/docs/#installation)

## Generate a Project Skeleton

```bash
cookiecutter --replay-file cookiecutter-talk.json https://github.com/reka/cookiecutter-typer-crud
```

Recommended:

* Move into another directory.
* Adjust the path of `cookiecutter-talk.json`

This way, you'll have the generated project in a separate git repository.
