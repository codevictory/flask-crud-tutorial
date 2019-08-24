# Flask Tutorial
CRUD web app made with Flask. Done following tutorial on YouTube: <br>
https://www.youtube.com/watch?v=Z1RJmh_OqeA

# Live publication
https://flask-crud-app-tutorial.herokuapp.com/

# Building up
1. Install `virtualenv` with `pip3`and use it with cli command: `source env/bin/activate`
2. `python3 app.py` 
3. Listens by default to `localhost::5000`

# Structure
- Minimalistic
- Only handful of files. 

## Frontend
- HTML + CSS 
- Jinja constructs (ie. {% block head %} )

## Backend
- Single Python file 
- Flask Alchemy ORM. 

## Database 
- SQLite

## Runtime environment
- HTTP server: Gunicorn (https://gunicorn.org/)
- Hosted by Heroku: https://www.heroku.com/platform
