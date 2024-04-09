.\vph\Scripts\activate #for activating the environment
creating local package in virtualenv we create setup.py
for updating local package in current envirnment   pip install -e .
pip install -r requirements.txt  #to install packages from requirements.txt
pip freeze > requirements.txt #update newly installed packages
git init #initialize git repositary
python setup.py install writing -e . in requirements.txt
SET ENVIRONMENT VARIUABLE ON WINDOWS OR  use export command with variable name and key or create a .env file
from dotenv import load_dotenv

load_dotenv()  # take environment variables from .env.
