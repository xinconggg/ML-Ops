# Build CI/CD Solution

## Overview

Implementation of Continuous Integration (CI) and Continuous Deployment (CD) processes using a Makefile and the Click test runner. Linting, formatting, refactoring, and testing on a Python script will be performed to ensure its quality and functionality.

## Goals

1. Understand the importance of CI/CD processes in MLOps.
2. Learn how to use a Makefile for automating linting, formatting, refactoring, and testing.
3. Gain experience in writing tests for command-line tools using the Click test runner.

### Lab Tasks

1. Source the virtual environment:\
   `source /home/coder/venv/bin/activate`
2. Run the following steps of the Makefile:
   - `make lint`
   - `make format`
   - `make refactor`
   - `make test`

3. Run the following command-line tool and then write a test for it using the Click test runner:
   - Write a test for the `add_cli` functionality of the `main.py` function in the `test_main.py` test file.
   - Use the test for `./main.py --help` as a guide.

### References

You can view this lab in GitHub here: [Coursera-MLOPs-Foundations-Lab-1-CICD](https://github.com/nogibjj/Coursera-MLOPs-Foundations-Lab-1-CICD)
