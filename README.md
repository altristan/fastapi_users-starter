This is a template for testing [fastapi-users](https://github.com/fastapi-users/fastapi-users). This code is taken from their documentation, and the database is specified to be postgres, while the ORM is SQLAlchemy.

To test, we need to have a database instance. Follow the instructions from this minimal [docker-postgres template](https://github.com/altristan/docker-postgres)

Once the database is setup and running, start the server:
``` bash
python main.py
```

Navigate to ``localhost:8000/docs``. You can now test the API endpoints using swagger.