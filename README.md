# tons-tw/python-minimal-starter

> THIS IS THE WAY!

## Getting Started
```sh
# to install uv (package manager)
curl -LsSf https://astral.sh/uv/install.sh | sh

# to sync environment
uv sync

# to sync environment for production
uv sync --no-dev

# to start the application
uv run python src/main.py

# or

# to launch the jupyter lab
uv run jupyter lab
```

## Common Scripts
```sh
# to format the code
uv run pyproject-fmt .
uv run ruff format
uv run ruff check --fix

# to lint the code
uv run ruff check

# to add dependency
uv add <PACKAGES> # --dev

# to upgrade dependencies
uv sync --upgrade

# to active venv
source .venv/bin/activate

# to deactivate venv
deactivate
```
