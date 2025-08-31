# Python template

---

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier)

---

> Currently in development, come back later...

---

A typical template for Python projects. Has pretty strict linter settings.

## How to use this template

```bash
copier copy https://github.com/zsxoff/python-template ./my-project
```

## To Do

- Better project name, module name, description rendering in Jinja2 templates
- Better ruff rules
- Better mypy rules
- Dockerfile from <https://github.com/zsxoff/docker-python> combined with uv multi-stage
- SQL formatter
- Security checks
- Pylint
- wemake-python-styleguide
- Pyrefly
- Code coverage
- Profiling packages optional group

---

## Git configuration

- [gitignore](https://github.com/github/gitignore) - A copy of Python.gitignore from <https://github.com/github/gitignore>

## Git hooks

- [Lefthook](https://github.com/evilmartians/lefthook) - A Git hooks manager for Node.js, Ruby, Python and many other types of projects

## Linters and Formatters

- [Flake8](https://github.com/PyCQA/flake8) - Linting tool for Python code
- [Flake8 Pydantic](https://github.com/Viicos/flake8-pydantic) - A flake8 plugin to check Pydantic related code
- [Flake8-pyproject](https://github.com/john-hen/Flake8-pyproject) - Flake8 plug-in loading the configuration from pyproject.toml
- [Mypy](https://github.com/python/mypy) - Optional static typing for Python
- [Pyright](https://github.com/microsoft/pyright) - Static Type Checker for Python
- [Ruff](https://docs.astral.sh/ruff) - An extremely fast Python linter and code formatter, written in Rust

## Security

- [Bandit](https://github.com/PyCQA/bandit) - Bandit is a tool designed to find common security issues in Python code

## Testing

- [pytest](https://github.com/pytest-dev/pytest) - Simple powerful testing with Python
- [pytest-sugar](https://pypi.org/project/pytest-sugar) - A plugin for pytest that changes the default look and feel of pytest

## External tools configuration

- [EditorConfig](https://editorconfig.org/) - Maintains consistent coding styles across editors and IDEs
- [Taplo](https://github.com/tamasfe/taplo) - A TOML toolkit written in Rust. In this template, it is used for `pyproject.toml`

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

This project is licensed under the terms of the [MIT](https://opensource.org/licenses/MIT) license (see [LICENSE](https://github.com/zsxoff/python-template/blob/main/LICENSE) file).
