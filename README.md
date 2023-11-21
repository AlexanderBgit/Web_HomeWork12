
    PostgreSQL database info
    Run uvicorn main:app --reload --host localhost --port 8000 --reload.
    Go to http://127.0.0.1:8000/docs to work with Swagger documentation.
    Аутентифікація наявна 
    Механізм авторизації за допомогою  JWT токенів: access_token та refresh_token

ПРИМІТКА Не забудьте підняти докер-контейнер з PostgreSQL і створити в ньому базу даних
