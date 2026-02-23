# python-build-demo

![CI](https://github.com/okami312/python-build-demo/actions/workflows/ci.yml/badge.svg)

## About

A short description of your project goes here.

## Installation

```bash
pip install -r requirements.txt
```

## Running Tests

```bash
pytest
```

## CI/CD

This project uses GitHub Actions for continuous integration. On every push or pull request to `main`, the pipeline will:

- Lint the code with flake8
- Run the test suite with pytest
- Generate and upload an HTML test report as an artifact
