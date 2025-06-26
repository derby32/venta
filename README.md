# Venta

A starter Python project managed with [Poetry](https://python-poetry.org/).

## Goals

This repository provides a clean foundation for building a Python application. The main objectives are:

- Provide reproducible dependency management using Poetry.
- Encourage keeping application code inside a dedicated `src` directory.
- Offer straightforward setup instructions for development.

## Setup

1. Install [Poetry](https://python-poetry.org/docs/#installation).
2. Install dependencies:
   ```bash
   poetry install
   ```
3. Activate the virtual environment when working on the project:
   ```bash
   poetry shell
   ```

## Dependencies

At this stage the project only relies on the Python standard library, but additional packages can be added with:

```bash
poetry add <package-name>
```

## Project Structure

```
venta/
├── pyproject.toml  # Poetry configuration
├── README.md       # Project documentation
└── src/            # Application source code
    └── venta/
        └── __init__.py
```
