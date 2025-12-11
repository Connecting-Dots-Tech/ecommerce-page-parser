## Pre-commit hooks
Set up a virtual environment in a way you prefer and install the packages:

[wily](https://wily.readthedocs.io/)

[pre-commit](https://pre-commit.com/)

[dead](https://github.com/asottile/dead)

[docstr-coverage](https://pypi.org/project/docstr-coverage/)

[bandit](https://pypi.org/project/bandit/)

[ruff](https://pypi.org/project/ruff/)

[pyright](https://pypi.org/project/pyright/)

Build wily cache
```bash
wily build
```
Set up the pre-commit environment
```bash
pre-commit install
```
What are [pre-commits](https://pre-commit.com/). To understand each pre-commit hook, refer to its respective documentation.
