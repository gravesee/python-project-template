# python-project-template

This template can be used for working on python packages as a developer. After cloning the repository run the following commands to set up the project in editable mode with dev dependencies:

```bash
$ python -m pip venv .venv

# windows
> .venv\\Scripts\\activate

# not-windows
$ source .venv/bin/activate

$ python -m pip install -e .[dev]

$ pre-commit install
```