# Real Estate

### Tech: Django, Python, HTML, CSS, JS
##### To run the project

- Clone the repository
- Initialize the virtual environment with command: 
    Mac/Linux: source path-to-venv/bin/activate
    Windows: path-to-venv/bin/activate
- To install the dependencies: pip install -r requirements.txt
- To Check whether the dependencies have installed: pip list
- Run python manage.py runserver. The application opens by default on port 8000.
- After that, make initial migration:
    - python manage.py makemigrations
    - python manage.py migrate
- Scripts are present in script folder to initialize the models and other prerequisites.
    - Create super user by running the script createsuperuser.py: python scripts/createsuperuser.py
    - Initialize requisite Data models running the script initializeDatabase.py: python scripts/initializeDatabase.py
- If everything went well, you will be able to login to admin console and view all the models populated.
    - Admin username: admin
    - Admin password: 12345
