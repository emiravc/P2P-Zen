# P2P Zen Bot's Panel & API

<a href="https://github.com/python/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)

Our database works perfectly fine however, it is still underconstruction. There are some debuggings that we have to.
#Better way to view, manage and access [P2P Zen](https://github.com/emiravc/P2P-Zen-Bot) contents.

In order to run this directory, follow the following commands in your terminal:
##Install poetry
```
poetry install
poetry config 
```
##Setting up virtual enviroment
```
virtualenvs.in-project true
source .venv/bin/acitvate
```
##Call the neccessary files
```
python manage.py migrate
python manage.py initdb
python manage.py runserver
```
Once you are done launch the specified local website in your browser and login to Django with your specified email and password.

After that execute [P2P Zen](https://github.com/emiravc/P2P-Zen) in an another terminal. At the end of execution, bot will send django to access. By the end of this P2P Zen bot should work totally fine.

# 2021 Hackathon Code The Change TEJBarbarians
