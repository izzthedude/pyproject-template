# pyproject-template

This is just a simple Python project template for my own convenience. It includes tools
and configurations that I commonly use throughout my Python projects.

### Highlights

- Uses **pip** with **pyproject.toml** as project/dependency management
- Includes basic dev dependency groups:
  - `dev`
  - `dev-lint`
- Includes configurations for **pre-commit** and the linting/formatting tools I
  normally use.
- Includes GitHub Actions workflow for checking code.
- Includes basic Issue and Pull Request templates.

## Usage

### Create repo

1. Click on `Use this template` and set a name for your repo.
2. Clone your repo.
3. Find all instances of `FIXME` throughout the project (file names, texts, etc.)
   and modify them accordingly.
4. Replace anything else with whatever you want (dependencies, Python version, etc.)
5. Delete the template's section of the `README.md`.
6. ???
7. Profit

By the time you get everything set up, there shouldn't be any `FIXMEs`.

### Use project

1. Setup virtual environment: `python -m pip venv .venv`
2. Install project dependencies with: `pip install -e .`
   - Optionally, with dependency group: `pip install -e .[group-name]`
3. Install pre-commit hooks: `pre-commit install`
   - To run manually: `pre-commit run`
   - To run on all files: `pre-commit run --all-files`

### FIXMEs

- `FIXME_PROJECTNAME`: Your project name
- `FIXME_PROJECTDESCRIPTION`: Your project description
- `FIXME_NAME`: Your name
- `FIXME_EMAIL`: Your email


# FIXME_PROJECTNAME

## Table of Contents

## Installation

## Usage

## Development

## License
This project is licensed under **GPL-3.0**, see the [LICENSE](LICENSE) for more details.
