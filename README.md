# Python template

> Currently in development, come back later...

---

## To Do

- Better ruff rules
- Better mypy rules
- Dockerfile from <https://github.com/zsxoff/docker-python>
- Copier template
- SQL formatter
- Security checks
- Pylint
- wemake-python-styleguide
- Pyrefly
- Code coverage

---

A typical template for Python projects. Has pretty strict linter settings.

## Tools setup

macOS:

```bash
brew install uv taplo
```

Arch Linux:

```bash
sudo pacman -S --needed uv taplo
```

## Git configuration

- [gitignore](https://github.com/github/gitignore) - A copy of Python.gitignore from <https://github.com/github/gitignore>

## Git hooks

- [Lefthook](https://github.com/evilmartians/lefthook) - A Git hooks manager for Node.js, Ruby, Python and many other types of projects

## Linters and Formatters

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
