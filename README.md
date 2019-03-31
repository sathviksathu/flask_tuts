To make sure your Python installation is functional, you can open a terminal window and type python3, or if that does not work, just python. Here is what you should expect to see:

$ python3
Python 3.5.2 (default, Nov 17 2016, 17:05:23)
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> _

Creating virtual environment, where you download all Flask related packages
python3 -m venv venv

Activating virtual environment
conda activate venv

Installing Flask
pip install flask
pip install flask-wtf -->for forms
pip install flask-sqlalchemy -->for databases, wrapper arounf SQLAlchemy
pip install flask-migrate --> for handling database changes, almost like git
pip install flask-login --> for handling login related 


mkdir app

add __init__.py to app directory where initialisations of all the instances are made
add routes.py to app direcctory where all the URL requests to app are routed to corresponding view

Flask needs to be told how to import it, by setting the FLASK_APP environment variable:
 export FLASK_APP=hello.py

 Run the application using 
 flask run

 templates folder has all the views



