# Project 1

Web Programming with Python and JavaScript

### Books.

### Harvard UNIVERSITY(CS50 Web Programming with Python and JavaScript)

This project is a collection of more than 4500 books. Here, you can find books with their detail information like ISBN, year, author, etc. You can see the rating for the book you desired after you logged in here. You can submit review to any book you like and comment it as well.

I have added "Goodreads" API too, from where you can see a book's global desire with its rating number and average rating from readers world wide.

And the project has also API, you can get information from The database and build your own web application.

# Description of each file

- `application.py` the main app file  and ORM to setup the database
- `import.py` used to import csv data into a configured database  
- `helpers.py` Decorate routes to require login
- `books.csv` csv data  
- `requirements.txt` dependencies to install
- `database.sql` create the tables.

Template descriptions:

- `layout.html` base template with common structure user can search and logout
- `results.html` books details
- `login.html` after user /invalid login credentials
- `register.html` user can register
- `index.html` search results page
- `book.html` display the book details, user can review and comment the book
- `error.html` error message

### Registration

username and password.

### Login

Log in using username and password.

### Logout

Logged in users should be able to log out of the site.

### Import

Import books.csv into PostgreSQL database.

### Search

Once logged in, search for ANY matches on a new page.

### Book Page

Book details and reviews users left on my page.

### Review Submission

One review per user: a rating from 1 to 5 and a review text (optional).

### Goodreads Review Data

Display the average and number of ratings.

### API Access

GET request to your website’s /api/<\isbn> route. Output a json file.
Otherwise, Invalid book ISBN.

### Create a virtualenv
$ python3 -m venv myvirtualenv

### Create database
ref: database.sql file

### Install dependencies
$ pip3 install -r requirements.txt

### ENV Variables
$ export FLASK_APP=application.py # flask run
$ export DATABASE_URL="Heroku Postgres DB URI"
$ export GOODREADS_KEY"="Goodreads API Key" [Here](https://www.goodreads.com/api)

### IMPORT CSV FILE

$ python import.py

Screencast presentation: [here](https://youtu.be/7PNRYJ40fLM)

