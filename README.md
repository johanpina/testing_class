# testing_class
Este repo contiene un ejemplo de backend y un frontend simple para realizarle pruebas unitarias y de integración.

---

## Configuraciòn inicial del proyecto

Generar el ambiente

`python -m venv .venv`

### En windows activar el ambiente

`.venv/Scripts/activate`

### En macOs o Linux

`source .venv/bin/activate`

### Instalar los requerimientos del proyecto

`pip install -r requirements.txt`

## Ejecutar el programa localmente

`uvicorn main:app`

ir a `localhost:8000/docs` en el navegador


### Ejecutar las pruebas

`cd testingClass`

`pytest test_app.py`
