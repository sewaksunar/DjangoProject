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
## Get inside virtual env
```
pip shell
```
### WrokSpace
Create project 
```
django-admin startproject firstproject
```
a folder is creater which is "firstpriject" also inside it another folder is created with same name which contain differnt configuration for our whole project

we can use ``` django-admin ``` or ```manage.py`` but we use second one

## To create projects
***note:** insdure cmd is in ```firstproject``` folder directrix
```
python manage.py startapp firstapp
```
