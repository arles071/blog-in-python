#Como utilizar esta pagian para hacer prueba:

paso 1:
En windows ejecutar el comando:
    entorno_virtual\Scripts\activate

paso 2:
comando:
    flask
    set FLASK_APP=app.py
    set FLASK_ENV=development
    flask run

paso 3:
Modificar en los datos para consultar o crear en base de datos
    app.config['SQLALCHEMY_DATABASE_URI'] ='mysql+mysqlconnector://root_web_python:password@localhost/web-python'
        root_web_python = es el nombre de usuario de base de datos.
        password = clave de base de datos.
        localhost = host donde se encuentra la base de datos.
        web-python = nombre base de datos.


