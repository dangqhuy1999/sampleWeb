Step by step:
	python3 -m venv venv
  346  source venv/bin/activate
  347  pip install click
  348  pip install flask flask-sqlalchemy
  349  pip install gunicorn
  350  gunicorn -b 0.0.0.0:8000 app:app # chay file app.py
  353  gunicorn -b 0.0.0.0:8000 app2:app # run file app2.py
