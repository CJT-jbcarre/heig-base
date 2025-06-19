# README

## Dependencies Management

- [`asdf`](https://asdf-vm.com/) manages python version at the system level
- [`uv`](https://docs.astral.sh/uv/) manages the python version and the packages
- [`quarto`](https://quarto.org/): open-source scientific and technical publishing system

## Set the Environment

```{shell}
uv venv --python 3.11.11
source .venv/bin/activate
uv pip install -r pyproject.toml
```

## Build the Report

```{shell}
uv run quarto render main.qmd
```
