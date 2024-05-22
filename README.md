# Exemple de README

Això és un [enllaç](https://google.com) i això són **negretes** i *cursiva* i ara ve una llista:

* hola
* que
* tal

Potser vols una llista numerada:

1. tot
2. bé
3. gràcies

## Un títol de nivell 2

I un troç de codi

    apt-get install virus

O aixó també és un troç de codi:

```python
a = 2 + 3
```
També pots integrar-ho `a=2` al paràgraf. lkfdk

---

# Desplegament de l'aplicatiu
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
