# Data Science Project Template

This repository provides a minimal and structured template for starting a new data science project using Python.

It includes:

- Dependency management with `uv`
- Code formatting with `black`
- Linting and import sorting with `ruff`

## Usage

To create a new project from this template:

```bash
gh repo create your-project-name --template gaeldatascience/template-project
cd your-project-name
uv venv
uv pip install --requirements pyproject.toml
```
