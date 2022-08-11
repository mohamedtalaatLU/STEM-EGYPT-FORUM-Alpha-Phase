# STEM-EGYPT-FORUM-Alpha-Phase
================================
This is the repository of STEM EGYPT FORUM, a platform intended to bring all STEMmers from all over the Arab Republic of Egypt to a one place\!
================================
INTERPRETER: -
PYTHON (3.9 or newer)
================================
REQUIRED EXTERNAL PACKAGES: -
flask (2.2.2 or newer)
flask_bcrypt (1.0.1 or newer)
flask_login (0.7.0 or newer)
================================
FEATURES: -
-It supports operations like registering new users, logging-in, and logging-out.
-The privacy of the users is secured using the flask_bcrypt hashing algorithm in order to increase the safety of the website.
-An SQLite3 database is used to accomodate any number of users.
-A database generating, and manipulating tool has been also developed, and provided to offer flexibility when testing certain functions of the website and the database.
================================
MANUAL(FOR PERSONAL SETUP): -
After installing the prerequisites mentioned above, download this package and run DB_Gen.py (to initialize a database if not existent), then SEF_ALPHA_FRAMEWORK.py. It will instantly setup a webpage accessible through "localhost:5000" which redirects the user to the register page. (If a user is already registered, 
it is also possible to access the login portal through "localhost:5000/login").
================================
DATABASE GENERATOR/EDITOR MANUAl: -
Run DB_Gen.py and then type "help" (without quotes, case sensitive) to show all the available commands. (some may be set inoperational for testing purpooses.)
================================
