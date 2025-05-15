# README

## Dependencies Management

- `asdf` manages python version at the system level
- `uv` manages the python version and the packages

## Set the Environment

```{shell}
uv venv --python 3.10.16
source .venv/bin/activate
uv pip install -r pyproject.toml
```
