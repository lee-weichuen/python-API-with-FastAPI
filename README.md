To install all the libraries:

-   pip3 install fastapi uvicorn

To run FastAPI:

-   cd into the folder where the main.py file exists.
-   python3 main.py

To access the docs:

-   http://0.0.0.0:8000/docs
-   http://0.0.0.0:8000/redoc

To create a task:

-   id field is not needed as it will be auto generated by UUID. So it can be deleted (to avoid confusion) when creating a task using the post request or just leave it (will eventually be replaced with a new id)

---------- Notes ----------

uvicorn

-   It's a simple web server to run FastAPI.

uuid

-   Stands for Universal Unique Identifier.
-   For creating unique id.

pydantic model

-   Help to automatically convert normal python class into valid JSON data that API needs.
