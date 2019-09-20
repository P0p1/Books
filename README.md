# Project 1

Web Programming with Python and JavaScript

# Create a virtualenv
$ python3 -m venv myvirtualenv

# Create database
ref: database.sql file

# Install dependencies
$ pip3 install -r requirements.txt

# ENV Variables
$ export FLASK_APP=application.py # flask run
$ export DATABASE_URL="Heroku Postgres DB URI"
$ export GOODREADS_KEY"="Goodreads API Key" ===> https://www.goodreads.com/api

# IMPORT CSV FILE
$ python import.py

Livrebooks project "livre" means  book in french. This project is a collection of more than 4500 books. Here, you can find books with their detail information like ISBN, year, author, etc. You can see the rating for the book you desired after you logged in here. You can submit review to any book you like and comment it as well.

We have added "Goodreads" API too, from where you can see a book's global desire with its rating number and average rating from readers world wide.

And the project has also API, just in case you want get information from The database and build you own web application.

#database.sql
contains SQL commands to create the database for this project.

#Templates
folder contains web pages files needed for the project incoded in jinja2.

#Static
folder contains logo and css, scss stylesheet for this project

#application.py
The file that contains Setting up database in create engine's argument.

#books.csv
find all the books information imported for this project executing python code written in import.py.
