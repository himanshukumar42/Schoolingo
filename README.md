# Schoolingo
A simple flask app that takes an image as input and returns the text within it.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
A simple flask app that takes an image as input and returns the text within it.
	
## Technologies
Project is created with:
* Python 3.9.5
* Flask 2.0.1
* React
	
## Setup
To run this project, Follow the below steps


Go to schoolingo flask app

```
cd schoolingo/flask-app
```

I always create a virtual environment called venv so that my project dependecies are installed separately (It's highly recommended). And activate
the virtual environment according to your operating system

```
$ python -m virtualenv venv
$ source venv/Scripts/activate
```

Install all python packages and dependencies from requirements.txt file in your python virtual environment 
```
$ pip install -r requirements.txt --no-cache-dir
```

Export the Flask App according to the file and environment and then run flask app

```
$ export FLASK_APP=app1
$ export FLASK_ENV=development
$ flask run
```

