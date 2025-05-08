# csc307-flask-backend

Sample code for CSC307 flask backend assignment

create a virtual environment:

python -m venv .venv

activate it:

source .venv/bin/activate

install requirements:

pip install -r requirements.txt

create the .env file with access to your monngo eb, then do the following:

export FLASK_APP=sample_backend.py
flask run

the app will start and listen on port 5000.

open a browser to http://localhost:5000 and you should see "hello class"
