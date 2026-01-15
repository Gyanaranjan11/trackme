setup app

Create virtual environment

python3.7 -m venv venv

For ubuntu

source venv/bin/activate

Install requirements

pip install -r requirements.txt

Run the app

python app.py

for Migration

Create migration

flask db migrate

Apply migration

flask db upgrade
