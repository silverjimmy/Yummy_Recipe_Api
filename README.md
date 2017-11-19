# Challange3

#Yummy Recipe Api - FLASK

[![Build Status](https://travis-ci.org/silverjimmy/Yummy.svg?branch=development)](https://travis-ci.org/silverjimmy/Yummy)[![Coverage Status](https://coveralls.io/repos/github/silverjimmy/Yummy_Recipe_Api/badge.svg?branch=development)](https://coveralls.io/github/silverjimmy/Yummy_Recipe_Api?branch=development)

## Introduction
Flask API


## Installation

Read to Create a virtual environment to work on the project.

```
virtualenv "name of the venv u want"
```
Then Activate the venv using:
```
source "name of the venv u want"/bin/activate
```

* Navigate to the application directory:

```
cd Yummy_Recipes_Api
```

* Create a virtual environment to install the
application in. You could install virtualenv and virtualenvwrapper.
Within your virtual environment, install the application package dependencies with:

```
pip install -r requirements.txt
```

* Run the application with:

```
python run.py
```
* for tests run in terminal using:

```
pytest tests
```

#### URL endpoints

| URL Endpoint | HTTP Methods | Summary |
| -------- | ------------- | --------- |
| `/auth/register/` | `POST`  | Register a new user|
| `/auth/login/` | `POST` | Login and retrieve token|
| `/recipes/` | `POST` | Create a new Recipe |
| `/recipes/` | `GET` | Retrieve all recipes for user |
| `/recipes/<id>/` | `GET` |  Retrieve recipe list details |
| `/recipes/<id>/` | `PUT` | Update recipe list details |
| `/recipes/<id>/` | `DELETE` | Delete a recipe list |
| `/recipes/<id>/categories/` | `POST` |  Create categories in a recipe list |
| `/recipes/<id>/categories/<catergory_id>/` | `DELETE`| Delete a category in a recipe list|
| `/recipes/<id>/categories/<catergory_id>/` | `PUT`| update a recipe list category details|


##Note
Remember to set up ur postgres according to your system config for postrges.
