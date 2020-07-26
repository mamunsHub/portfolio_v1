# goto project root
cd YOUR_PROJECT_ROOT_DIRECTORY

# setup python virtual environment for project
virtualenv -p python3.6 .venv

# activate virtual environment
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt
