# My Personal Blog Website
## Functionality
&bull; Users need to register/login in order to comment on posts. <br>
&bull; Passwords are securely encoded with hashing and salting functions of the werkzeug.security package. <br>
&bull; User authentication is done with a flask_login object. <br>
&bull; Only Admin users can create and delete posts. <br>
&bull; Users can get in contact with the the owner(me) by sending a message, which gets transferred via email over a SMTP client session object. <br>
&bull; The App makes use of CKEditor (for creating posts and comments).  <br>
&bull; (Production) WSGI server is setup with Gunicorn to run the Live Python Application. PostgreSQL database is used for production. <br>
&bull; (Development) Development and testing is done locally with a SQLite database. <br>
## Topics covered
&bull; Python, HTML, CSS, Heroku, SQL <br>
&bull; Flask Web Framework <br>
&bull; SQL Databases <br>
&bull; Decorators <br>
&bull; OOP <br>
&bull; Functions <br>
## Packages
See requirements.txt for all packages and dependencies used.
