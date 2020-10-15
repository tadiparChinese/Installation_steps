# Installation_steps

1. Create Virtual Environment 
 - pip install pipenv
 - create a virtual environment : virtualenv .
 - Activate the Virtual Environment 
 windows:  .\Scripts\activate
==========================================================================

pip install virtualenvwrapper-win
mkvirtualenv venv

workon venv
 or ls
-> venv  src static
source venv/bin/activate


# Create a virtual environment to isolate our package dependencies locally
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

pip install django 
python -m django --version (to check the version)
django-admin --version
django-admin startproject projectName

for debugging tool bar --> search for
Django Debug Toolbar documentation
>>$ pip install django-debug-toolbar

for creating new app
python manage.py startapp app_name
you can name it core or main as standand convention

import *(mhanje all hoto)


after creating model
> python manage.py makemigrations 
>>python manage.py migrate
>> python manage.py createsuperuser

collecting all static>
> python manage.py collectstatic

>>python manage.py runserver

to check actual sqlcommands
>>python manage.py sqlmigrate <appName> <migrationNumber>
eg. >>python manage.py sqlmigrate blog 0001

use python decouple to hiding sensitive information, save the information in .env file



>node react tools
redux thunk(middleware)
axiosm, store, action
use fragments insted of div
states props 
st

object { }, array[ ],
list([ ]), map({ })


hustky -for checking problematic git push
eslint - for check the javascript code
chloropleth map for showing data visualization
immutable js for data structure
isomorphic react
require.js
 MobX
The idea behind Redux
>You have mainly three components store, reducer, and actions


cdpython hindi 92==89



for testing django app
 ==>selenium
==>LiveServerTestCase
==> Coverage

to activate virtualenv 
==> 
$ virtualenv env
$ cd env/Scripts/
$ . activate



django-admin startproject projectName
