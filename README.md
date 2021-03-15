# Jobly

[Warbler](http://alan-tseng-warbler.herokuapp.com "Warbler")  is a full stack Twitter clone built with a Flask backend, PostgreSQL database and SQLAlchemy ORM. The frontend uses Jinja for HTML templating, jQuery and Axios for certain features.

# App Highlights
* New users can log in / sign up
* Logged in users can edit their user profile
* Logged in users can follow and unfollow other users
* Logged in users can write messages
* Logged in users can like and unlike other users' messages
* Logged in users can explore and search for other users
* Logged in users can delete their profile

## Upcoming features / Future Plans for Implementation
* Users can delete their own messages
* Users can change their password

# Installation and Setup

1. Clone the [repository](https://github.com/atseng202/warbler)  
2. `cd warbler`   
3. Set up the virtual environment
* `python3 -m venv venv`  
* `source venv/bin/activate`
* `pip3 install -r requirements.txt`
4. Create database
* `createdb warbler`  
* `createdb warbler-test`
* `python3 seed.py`  
5. Run the server
* `flask run`

## Running Tests
* To run all tests: `python3 -m unittest`
* To run specific test file: `python3 -m unittest test_FILENAME.py`

# Technologies Used
1. [Flask](https://flask.palletsprojects.com/en/1.1.x/) - Backend framework
2. [Flask-WTForms](https://flask-wtf.readthedocs.io/en/stable/) - Integrates Flask with WTForms library, includes validations and CSRF protection
3. [PostgreSQL](https://www.postgresql.org/) database
4. [SQLAlchemy](https://www.sqlalchemy.org/) - Object Relational Mapper (ORM) for interacting with database
5. [Jinja](https://palletsprojects.com/p/jinja/) - HTML Templating for views
6. [Axios](https://github.com/axios/axios) - Promise-based HTTP client for asynchronous requests

# Authors
My partner for the project was [@d-lee84](https://github.com/d-lee84)
