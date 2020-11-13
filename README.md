# Cookiecutter python_project

## Features

* testing with pytest including code coverage (for [coveralls.io](https://coveralls.io/))
* formatting with black (including a pre-commit hook)
* [linting](https://www.pylint.org/) with [flake8](https://flake8.pycqa.org/en/latest/) (configured to play nice with [black](https://github.com/psf/black))
* ready to use with [Travis CI](https://travis-ci.com/)
* automatic publishing to pypi via Github Actions upon new release
* [Sphinx](https://www.sphinx-doc.org/en/master/index.html) documentation with [automatic](https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html) API documentation from [docstrings](https://numpydoc.readthedocs.io/en/latest/)
* Jupyter notebooks can be [rendered with sphinx](https://nbsphinx.readthedocs.io/en/0.8.0/) (place them inside docs/examples folder)
* vscode configuration for using black and flake8 and [flake8-docstrings](https://pypi.org/project/flake8-docstrings/) ( with numpy doc style)

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

* Remember to put the PyPi token in Settings -> Secrets of the repo. Update token with a new one with limited scope.
