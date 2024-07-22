## que es flask?

- Es un microframework 

## Ventajas

- Muy facil de usar
- Es ideal para desarrollar rapido


## Code
``` python
from flask(module) import Flask(class)

```
##  Correr app  

``` python
flask  --app hello run

```

## Depurate
``` python
flask  --app hello --debug run

```

## Routes y views


## Varias Rutas a una misma funcion
``` python

@app.route('/')
@app.route('/index')
def index():
    return '<h1>Hola Mundo</h1>'

```


## Variables Por url
``` python

@app.route('/hello/<name>')
def hello(name):
    return f'Hola como estas {name} ?' 

```


## tipos de variable Por url
``` python
#path
#string
#int
#uuid

@app.route('/hello/<int:name>')
def hello(name):
    return f'Hola como estas {name} ?' 

```

## Escape  
Por defecto flask renderiza el codigo como html , la funcion escape se utiliza para que no pueda injectarte codigo por la url  
Ejemplo: http://127.0.0.1:5000/code/%3Cscript%3Ealert(%22bad%22)%3C/script%3E
``` python
from markupsafe import escape
@app.route('/code/<path:code>')
def code(code):
    return f'<code>{escape(code)}</code>'

```

## Templates y jinja

- Por defecto flask busca los templates en la carpeta **/templates**.


## BLUE PRINT  
Permite organizar las vista y modulos cuando el proyecto es mas grande.
- Construir modulos
    - el modulo debe tener el archivo init_py.
    - Separar aplicaciones en modulos(ejemlplo auth/ otras funcs)

##  Base de datos

Viene un complemento que se llama SQL ALCHEMY.  
Permite integrarse facil con bases de datos.  
Por ejemplo con Oracle, Mysql, sqlite, etc.  
Permite realizar migraciones automaticas.  




## Sheel flask 





``` python
flask --app todor shellf

```



## Usuarios 

- Es mala practica informa que el usuario es incorrecto porque si le deja de aparecer ese mensaje un hacker puede intuir
  que el usuario existe y le faltaria averiguar la contraseña.


## API REST