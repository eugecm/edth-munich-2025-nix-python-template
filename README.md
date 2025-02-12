# Nix template for a Python project

This Nix template uses [uv](https://github.com/astral-sh/uv) and
[uv2nix](https://github.com/pyproject-nix/uv2nix) to manage and build a simple
Python application.

## Running

To enter the dev shell:
```bash
# This will set up the correct version of python and uv.
nix develop
```

You can now manage the project as usual using `uv`:
```bash
# Add a dependency
uv add pandas

# Run program
uv run hello
```
