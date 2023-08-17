# Deephaven Plugin for json

The Deephaven Plugin for json.

Currently in development.

## Build

To create your build / development environment:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip setuptools build deephaven-plugin
```

To build:

```sh
python -m build --wheel
```

produces the wheel into `dist/`.

To test within [deephaven-core](https://github.com/deephaven/deephaven-core), note where this wheel is stored (using `pwd`, for example).
Then, follow the directions in the top-level README.md to install the wheel into your Deephaven environment.