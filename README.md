# Cookiecutter python_project

## Features

* testing with pytest including code coverage
* formatting with black (including a pre-commit hook)
* linting with flake8 (configured to play nice with black)
* ready to use with Travis CI
* automatic publishing to pypi via Github Actions
* Sphinx documentation with automatic API documentation from docstrings
* Jupyter notebooks can be rendered with sphinx (place inside docs/examples folder)
* vscode configuration for using black and flake8 and flake8-docstrings ( with numpy doc style)

## Usage

`
cookiecutter https://github.com/bleykauf/cookiecutter-python_project
`

Development requirements are proviced as `requirements.txt` for pip and `environment.yml`
 for conda. Install those if needed.




Initialize git repo and install pre-commit hooks:

```
git init
pre-commit install
```
