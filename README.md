# Dotfiles

My dotfiles

## Create virtual environment and install requirements

```sh
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
deactivate
```

## Install pre-commit hooks

```sh
pre-commit install
```

## Run playbook

```sh
inv play
```
