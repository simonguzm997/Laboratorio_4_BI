# Laboratorio_4_BI


## Miembros

- Carlos Figueredo - 201813445
- Carlos Ballén - 200821488
- Simón Guzmán - 201533711

## Instalar dependencias

Para empezar, se necesita instalar las dependencias que se utilizan en el proyecto, para esto se usa:

`pip install -r requirements.txt`

## Despliegue

El API se ejecuta con el comando:

`uvicorn main:app --reload`

## Funcionamiento API

Para el funcionamiento del API haremos uso de dos endpoints:

- localhost:8000/predict  -   Este realiza la predicción para un solo caso.

- localhost:8000/r2_model  -   Realiza la predicción R^2 del modelo.
