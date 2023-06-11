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

- Export variables
    ```bash
    export FLASK_SECRET_KEY=your_key
    export FLASK_APP=animes
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
- [RESTful Auth with Flask](https://blog.miguelgrinberg.com/post/restful-authentication-with-flask).
- [Werkzeug Docs](https://werkzeug.palletsprojects.com/en/2.3.x/utils/).
- [Flask make_response method](https://tedboy.github.io/flask/generated/flask.make_response.html).
- [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.0.x/models/#defining-models).

## ToDo
- Add tests.
- Implement logout (JWT token blacklisting).

## Changelog

- [1.1](https://github.com/marianogg9/flasking/commit/a73a18edddeaa90fc9bbe7cfae4b283da60b7894)
    
    - added JWT support.
    - added API documentation.

- [1.0](https://github.com/marianogg9/flasking/commit/0befc32708fec0c663d8d987803dec61ef661b60)
    
    - Basic authorization support.