# framed
Landing Page for the annual Art Exebition of IIT Jodhpur.

# Setup
- Install [python](https://www.python.org/downloads/) in your environment(pre-installed on Ubuntu).

- Navigate to the cloned repository.
    ```
    cd <project_directory_name>     # framed
    ```
- Install `pipenv` for dependency management
    ```
    pip install pipenv
    ```
- Activate virtual environment, if you don't want to activate env, use `pipenv run` to run python scripts
    ```
    source "$(pipenv --venv)"/bin/activate
    ```
- Install Dependinces
    ```
    pip3 install -r requirements.txt
    ```
- Make database migrations
    ```
    python manage.py makemigrations 
    python manage.py migrate 
    ```
- Create a superuser
    ```
    python manage.py createsuperuser 
    ```
- Run development server on localhost
    ```
    python manage.py runserver 
    ```

