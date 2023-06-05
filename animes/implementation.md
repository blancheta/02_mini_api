# Implementation

This is an API to list an Anime from local DB.

## Components
- Flask.
- SQLAlchemy.
- JWT support.

## How to run
- Use a virtualenv
    ```bash
    python3.9 -m venv .venv
    ```
    (and activate it)
    ```bash
    source .venv/bin/activate
    ```

- Install dependencies
    ```bash
    pip install -r requirements.txt
    ```

- Run
    ```bash
    flask run
    ```

- See API documentation
    ```bash
    pdoc animes
    ```
    It will open a browser in `localhost:8080` with the API documentation.

## Resources
- [Real Python Flask JWT auth tutorial](https://realpython.com/token-based-authentication-with-flask/).
- [RESTful Auth with Flask](https://blog.miguelgrinberg.com/post/restful-authentication-with-flask) by Miguel Grinberg.
- [Werkzeug Docs](https://werkzeug.palletsprojects.com/en/2.3.x/utils/).
- [Flask make_response method](https://tedboy.github.io/flask/generated/flask.make_response.html).
- [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.0.x/models/#defining-models).