# mohit-flask-test
Known as Mohit-Flask-Test for now. Actually called Twitter-4-Men (yeah, it's that bad..)
## Usage
The software is issues under the Apache license, meaning you could freely modify it.

Written in HTML, CSS, Python's Flask Framework, and Jinja2 Templating.

To run your own instance, clone the repository as
```
git clone https://www.github.com/snazzycoder/mohit-flask-test.git
```

Then, change current directory to it using `cd mohit-flask-test` command

Now, install all the requirements using pip mentioned in requirements.txt
```
pip install -r requirements.txt
```

To run it in `development` environment, run
```
export FLASK_ENV=development
export FLASK_APP=app.py
flask run
```

To run it in `production` environment, run
```
export FLASK_ENV=production
export FLASK_APP=app.py
flask run
```
## Backend and security
The passwords are hashed using SHA-256 alogrithm using the `hashlib` module in python. The databse is located in a `remotemysql.com` server.
## History
Help contribute to build a twitter alternative. Started off as an XI-Grader curious journey towards flask development. Looking forward to having support and see new users sign up.