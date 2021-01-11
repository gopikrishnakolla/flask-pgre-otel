# flask-pgre-otel
This shows integration of python code using flask web framework and SLQAlchemy for DB integration with PostgreSQL, and with OpenTelemetry for observability (esp. around tracing) and exporting traces via Jaeger exporter.

# how to run it locally
pip install -r requirements.txt

cd app

set FLASK_APP=app.py

flask db upgrade

flask run -h 0.0.0.0 -p 5000

http://localhost:5000/
