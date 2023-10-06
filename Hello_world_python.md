# Instalación de python

Primero revisamos si tenemos python3 instalado con: 

```
python3 --version
``` 

En este caso si esta instalado.

## Creación, compilación y ejecución del programa.

### Creación:
Creamos un archivo con extensión *.py* llamado Hello_world con el siguiente código:

```py
print("Hello World!")
```

### Compilación:
compilamos con el siguiente comando:

```
python3 -m py_compile hello_world.py
```

deberiamos obtener una carpeta llamada `__pycache__` donde se guardarn dichos archivos compilados.

Ahora debemos entrar en esa carpeta con:

```
cd __pycache__
```

### Ejecución:

Y ahora ejecutamos el comando:

```
python3 Hello_world.cpython-38.pyc
```