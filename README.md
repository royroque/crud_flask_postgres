# This is clone/fork off simplinnovation github repo of his implementation of:
# Basic CRUD: Flask & PostgreSQL

# NOTE: this can be used for our rest api testing
1. Clone this repo.
2. start docker-compose from docker folder<br/>
    This will download the pre-configured postgresql db container with the lin_flask table created<br/>
    OPTIONAL: check pgadmin localhost:5432 if table is created 
2. Open project in pycharm, run app.py<br/>
    navigate browser to http://localhost:5000/data
3. import postman collection:<br/>
    run get(all/one), post, put, delete<br/>
    validate with browser to http://localhost:5000/data
4. write your python request program using the same url, method, payload used in postman above
    
