# FILE: /py-playground/py-playground/README.md
# Py Playground

This is a simple repo to provide a KISS (keep it stupid simple) playground repo to test pythong stuff, ecosystem, tooling, infrastructure  AS EASY AS POSSIBLE.
The repo is meant to provide you a head start.
While the repo is create for my own individual python experiments, you are welcome to just use it as well.

## Dev Tooling

### Build System: Poetry

We ues poetry atm.

In older host systems, it might be necessary to define/upgrade the used python version in the venv

Make sure you have python 3.12 installed on your system.

Tell the venv that it should use 3.12

```bash
poetry env use /usr/bin/python3.12
```

### pre-commit

We use pre-commit as a pre-commit framework to run a set of checks before committing.

Make sure you have installed [pre-commit](https://pre-commit.com/)

To install local pre-commit hooks on your system, you need install it.
```bash
pre-commit install
```

### liniting: ruff

not yet integrated

### unit testing: pytest

not yet integrated

### virtualisation

beside poetry, we like to support a docker setup as well (not absolute necessary)

not yet integrated

### docs: justdocs

not yet integrated

### vscode tasks

define task to execute stuff.
