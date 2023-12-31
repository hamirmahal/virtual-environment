[![Run Python Script](https://github.com/hamirmahal/virtual-environment/actions/workflows/python.yml/badge.svg)](https://github.com/hamirmahal/virtual-environment/actions/workflows/python.yml)

# Setup

Run

```
python3 -m venv env/
```

in your terminal.

Then, restart your terminal or run

```
source env/bin/activate
```

# Installation

Run

```
pip list
pip install -r requirements.txt
pip list
```

in your terminal to install the packages listed in
[`requirements.txt`](requirements.txt).

To install a new package, run

```
pip list
pip install mypy # replace `mypy` with the package name
pip list
pip freeze > requirements.txt
```

in your terminal.

# Running

Run

```
python3 p.py
```

in your terminal.
