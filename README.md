# goto project root
cd YOUR_PROJECT_ROOT_DIRECTORY

# setup python virtual environment for project
virtualenv -p python3.6 .venv

# activate virtual environment
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt

# migration and runserver

python portfolio/manage.py makemigrations
python portfolio/manage.py migrate
python portfolio/manage.py runserver