# Data Science Project Template

This template is a data science project setup that provides a structured and organized starting point for your data science projects. It includes Cookiecutter for project templating, Pyenv for managing Python versions, and Poetry for dependency management. With this template, you can easily set up and manage your data science projects in a reproducible and efficient manner.

Inspired by [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)
A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.

## Project Description

Explain briefly what this project is about and what problem it aims to solve.

## Directory Structure

Explain the purpose of each directory in the project.

## Getting Started

Describe how to set up the project and get it running on a local machine.

## Dependencies

List the main dependencies required for the project and how to install them.

### Using Poetry and Pyenv for Python Dependency Management

1. Install `pyenv` <https://github.com/pyenv/pyenv> and `poetry` <https://python-poetry.org/docs/#installation> on your machine.

2. Install the appropriate Python version:

    ```{bash}
    cd ./project-name
    pyenv install 3.9.16
    pyenv local 3.9.16
    ```

3. Configure Poetry to create the virtual environment in the project root:

    ```{bash}
    poetry config virtualenvs.in-project true
    ```

4. Install all the dependencies with a single command:

    ```{bash}
    poetry install
    ```

5. Activate the virtual environment

    ```{bash}
    poetry shell
    ```

## Usage

Provide instructions on how to use the project, including example code and scripts.

## Contributing

Specify how others can contribute to the project. Mention guidelines for pull requests and contributions.

## License

Mention the license under which the project is distributed.
