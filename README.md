# Setting Up the Development Environment

To manage dependencies and create an isolated environment for this project, we use **Pipenv**.

> **Note:** Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design.

## Installation

First, install Pipenv using pip:

```bash
pip install pipenv
```

Pipenv will create a virtual environment and manage all package versions required for the application.

Next, install Django within the virtual environment:

```bash
pipenv install django
```

This ensures that all dependencies are contained within a dedicated virtual environment for your project.

## Activate the Virtual Environment

```bash
pipenv shell
```

## Workspace Setup

To create a new Django project, run:

```bash
django-admin startproject firstproject
```

This command creates a folder named `firstproject`. Inside it, another folder with the same name is created, which contains configuration files for the entire project.

You can use either `django-admin` or `manage.py` for project management, but typically `manage.py` is preferred for most tasks.

## Creating an App

**Note:** Ensure your current directory is inside the `firstproject` folder.

To create a new app, run:

```bash
python manage.py startapp firstapp
```

A new folder named `firstapp` will be created.

## Web Framework

Django is a powerful web framework that follows the Model-View-Template (MVT) architectural pattern.

## MVT Overview

- **Model:** Handles the data and database.
- **View:** Manages the logic and processing.
- **Template:** Controls the presentation layer (HTML).


