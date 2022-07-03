# Nbyula_Assignment
# Meet
## _Schedule Meet with terraformers

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Meet is a django based application for making schedule


## Features
- Can register user
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF


## Tech
- [Django](https://www.djangoproject.com)
- [Django-Rest-framework](https://www.django-rest-framework.org)

## Routes

```sh
        'GET': '/api/allAppointments/'
        'GET': '/api/upcomingAppointment/'
        'POST': '/api/scheduleAppointment/'
        'POST': '/api/register/'
        'POST': '/api/UpdateProfile/id/'
        'POST': '/api/offHours/'
        'DELETE':'/api/deleteUser/id/'
        'POST': '/api/token/'
        'POST': '/api/token/refresh/'
```
## Installation

having a virtual environment is good and in python3 we can do something like
```sh
pyhton3 -m venv env
source env/bin/activate 'activate virtual environment for mac and linux machine'
pip install django
django-admin startproject <your-project-name> .
```


## Postman




## Deployed

- [Meet-terraformers](https://meet-terraformers.herokuapp.com)

> Note: `add api/ in the end of routes` is required for Routes.
