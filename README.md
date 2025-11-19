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

## Running Tests

This template includes a minimal test suite using pytest.

Run all tests with:

```bash
uv run pytest
```

By default, tests are located in the `tests/` directory.

## Project Structure

```bash
project-root/
│
├─ src/
│   └─ main.py        # Entry point of the program
│
├─ tests/
│   └─ test_main.py   # Example test file
│
├─ pyproject.toml     # Project configuration
├─ README.md
└─ .gitignore
```

## Continuous Integration (GitHub Actions)

This project includes a GitHub Actions workflow that:

- Install **uv**
- Synchronizes dependencies
- Runs the test suite using pytest

The workflow file is located at:

```bash
.github/workflows/ci.yml
```

It runs automatically on every `push` and `pull_request` to the `main` branch.

## Customization

You can extend this template with:

- **ruff** for linting
- **mypy** for static typing
- **coverage** for test coverage
- Additional scripts or CLI tools
- Packaging options for libraries or executables

If you'd like help configuring any of these, feel free to ask!

## License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.
