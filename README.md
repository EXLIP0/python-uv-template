# Python UV Project Template

This repository provides a minimal template for starting a Python project using uv, a fast Python package manager and environment tool.

## Requirements

This project requires:

- **Python 3.11 or later**
- [uv](https://github.com/astral-sh/uv) installed on your system

## Installation

Install all project dependencies:

```bash
uv sync
```

This will create a virtual environment and install the dependencies declared in `pyproject.toml`.

## Running the Project

To run the project:

```bash
uv run src/main.py
```
