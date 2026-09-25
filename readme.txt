winget install Python.Python.3.12
py -3.12 --version
git --version
cd Desktop
cd 24-09-2026
git clone https://github.com/Joshua-Millao/App-TAREAS-113-4A-mvt.git
cd App-Tareas
py -3.12 -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py check
python manage.py runserver
