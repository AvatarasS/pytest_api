# Pytest API Testing Framework

This project is a basic pytest framework for testing API requests using <https://simple-books-api.glitch.me> as a testing sandbox. The framework shows how to test different HTTP methods and scenarios with API endpoints.

The framework also uses Allure reporter to generate test reports that are stored and displayed via GitHub Pages.

## Installation

To install the required environment, run the following commands:

- ```python -m pip install``` 
- ```--upgrade pip pip install```
- ```pipenv pipenv install --system ```

## Usage

To run all tests, use this command:

```pytest ```

To run a specific test, use this command with the name of the test:

```pytest -k <name of the test> ```

## Reporting

The test report is generated automatically after each test run, overriding the previous report. To view the report, use this command:

```allure serve reports ```
