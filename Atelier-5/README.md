# Table of Contents

- [Installation](#installation)
  - [Prerequisites](#prerequisites)
    - [Create The virtual environment](#create-the-virtual-environment)
  - [Install Dependencies](#install-dependencies)
  - [Add Dependencies](#add-dependencies)
  - [Run the Application](#run-the-application)
    - [CLI](#cli)
    - [Notebook kernel](#notebook-kernel)

# Installation

## Prerequisites

- [Python 3.12](https://www.python.org/downloads/windows/)
- [Poetry](https://python-poetry.org/docs/#installation)

### Create The virtual environment

```bash
py -3.12 -m venv venv
poetry env use venv/Scripts/python.exe
```

## Install Dependencies

```bash
poetry install
```

## Add Dependencies

```bash
poetry add <dependency>
```

## Run the Application

### CLI

```bash
poetry run python main.py
```

### Notebook kernel

In order to use the virtual environment in a notebook select the environment with the name that was created by poetry.

You can see all poetry environments with the following command.

```bash
poetry env list
```
