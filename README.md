# WebApp

Ejercicios de Aplicaciones Web con Python3, SQLite3 y web.py

## 1. Crear un Virtual Environment

Crear el virtual environment para la instalación de las librerías necesarias para el proyecto.

````shell
python3 -m venv .venv
````

## 2. Crear el archivo **.gitignore**

Crear el archivo **.gitignore** para configurar los recursos que no necesitamos que se sincronicen con el repositorio.

````shell
*.pyc
__pycache__/
.venv/
````

## 3. Activar el virtual environment

Activar el **virtual environment** para realizar la instalación de las liberías necesarias.

````shell
source .venv/bin/activate
````

## 5. Actualizar **PIP**

Actualizar el instalador de paquetes de python **pip**.

````shell
pip install --upgrade pip
````

## 5. Crear el archivo **runtime.txt**

Crear el archivo **runtime.txt** con la versión utilizada de python3.

````shell
python3 -V > runtime.txt
````

## 6. Instalar el micro-framework **web.py**

Instalar el micro-framework **web.py** en el ambiente virtual (virtual environment)

````shell
pip install web.py
````

## 7. Crear el archivo **requirements.txt**

Crear el archivo **requirements.txt** con las versiones de las librerías instaladas en el ambiente virtual.

````shell
pip freeze > requirements.txt
````

## 8. Indexar el contenido del repositorio

Indexar todo el contenido del repositorio para incluir todos los archivo nuevos y las modificaciones realizadas al código.

````shell
git add .
````


