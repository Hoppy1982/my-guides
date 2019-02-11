#Django Guide

##Prerequisites
* Install Python
* Install virtualenvwrapper-win (if windows obvs)
* Install Django
* _<optional>_ Setup Database


###Install Python
* https://www.python.org/downloads/
* Install to any directory. (eg c:/python)
* Edit environment variable (user) path to include the directory containing python.exe and the ..python/scripts directory

###Install Virtualenvwrapper-win
* $ pip install virtualenvwrapper-win (from any dir, doesn't matter, it will put the scripts in python/scripts)
* Create a directory to store virtual environments (eg. c:\python envs)
* New user environment variable (WORKON_HOME: (eg. c:\python envs))
* See https://pypi.org/project/virtualenvwrapper-win/ for full list of virtualenv commands

###Install Django (must be done for each django project)
* cmd prompt / shell 

###setup database _(sqlite3 as example)_


##Steps
* Create or clone project
* Create a new virtual env & point it at the project
* Install Django

###Create a new python virtual env & point it at the project
* cmd prompt / shell 
* $ mkvirtualenv -a <path to django project> <virtual env name>
* example for above $ mkvirtualenv -a 'c:/python envs/project-one-env'
  
###Install Django
* cmd prompt / shell
* $ workon <virtual env name>
* $ pip install django
* verify with $ django-admin --version
