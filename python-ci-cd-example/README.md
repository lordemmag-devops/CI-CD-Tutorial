
![CI](https://github.com/lordemmag-devops/python-ci-cd-example/actions/workflows/ci.yml/badge.svg)

# Simple Calculator App

A basic Python calculator with add, subtract, multiply, and divide functions. Includes unit tests using pytest.

## Run code locally
Set up a virtual environment (recommended)

- cd python-ci-cd-example
- python -m venv venv
- source venv/bin/activate # On Windows: venv\Scripts\activate

## Install requirements

pip install -r requirements.txt

## Run tests

touch app/__init__.py
touch tests/__init__.py
update pytest to PYTHONPATH=. pytest

run "pytest" on terminal.

## Add CI Pipeline (GitHub Actions)

modify code to test the CI created

## Add Code Quality Tools (Linting & Formatting)

- update requirements.txt: add black, and flake8 then install them.
- pip install -r requirements.txt

## Create a Formatter Check Workflow

- update your GitHub Actions to include code quality checks.

## Add a Build Status Badge to README.md

- Check the first line of page.

## Set up Continuous Deployment (CD)
CD means automatically deploying your app when CI passes
Since this is a basic calculator app, there's nothing to deploy.
