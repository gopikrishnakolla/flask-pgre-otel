# flask-pgre-otel
pip install -r requirements.txt

cd app

set FLASK_APP=app.py

flask db upgrade

flask run -h 0.0.0.0 -p 5000

http://localhost:5000/
