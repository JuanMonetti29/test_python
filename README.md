# Mi trabajo
![](https://www.josedomingo.org/pledin/assets/wp-content/uploads/2018/03/flask.png)

## INDICE

1. [Desplegament](#desplegament-de-laplicatiu)
2. [Requisitos](#requisits-previs)
3. [Configuracion](#configuració-de-lentorn-virtual)
4. [Modos](#modo-remoto-o-local)


## Desplegament de l'aplicatiu
Este projecto consiste es una aplicacion la cual tiene la funcion de utilizar un entorno virtual basado en python, a continuacion explicare unos pocos pasos necesarios para poder llevar a cabo este projecto ya sea de ocmo remoto o modo local.

## Requisits previs
Lo mas importante y fundamental es tener claramente instalado Python en tu sistema, si no lo tienes puedes descargarlo desde el sigueinte enlace.(https://www.python.org/downloads/)

## Configuració de l'entorn virtual
Para no los que no saben que es un entorno virtual este es un espacio aislado encargado de guardar todas las dependencias te du projecto, aun asi para poner tener mas informacion sobre el funcionamiento de este podeis consultar este enlace con informacion.(https://docs.python.org/3/tutorial/venv.html)

Para poder crear esto entorno visual debes usar el siguiente comando: python -m venv env

Este seria poder activarlo: .\env\Scripts\activate

Instalacion de dependencias: pip install -r requirements.txt

Iniciacion de la aplicacion: python app.py

## Modo remoto o local

La utilizacion de uno u otro es muy sencilla, a continuacion os mostrare el unico cambio necesario para que la aplicacion funcione en modo remoto o en modo local.

Modo remoto: REMOTE_MODE = True

Modo local: REMOTE_MODE = False
