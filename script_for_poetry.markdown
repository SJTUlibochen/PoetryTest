# Script for Poetry

## Add Source

```bash
poetry add source <name> <url/pypi/simple>
```

for example:

```bash
poetry add source sjtug https://mirror.sjtu.edu.cn/pypi/web/simple
```

Poetry only supports configure source for certain project, you cannot set a global mirror for Poetry like pip.

## Install Package

```bash
poetry add <package>
```

## Remove Package

```bash
poetry remove <package>
```

## List Packages

```bash
poetry show
```

## Update Package

```bash
poetry update
```

## Update poetry.lock According to pyproject.toml

```bash
poetry lock
```

## Update Poetry Venv According to poetry.lock

```bash 
poetry install
```

## Transfer poetry.lock to requirements.txt

```bash
poetry export -f requirements.txt --output requirements.txt
```
