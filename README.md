# Hello From

This package illustrates ...

Following PEP517, the setup is not executed by your python environment, but by an environment built ad-hoc at install time.
The packages to be retrieved for the installation are specified in pyproject.toml. Note that numpy needs to be included in order to compile extensions with f2py.

```toml
[build-system]
build-backend = 'setuptools.build_meta'
requires = [
    'setuptools >= 43.0.0',
    'numpy'
]
```
