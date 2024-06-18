# Tarea 02 - Procesamiento de Datos Masivos

## Integrantes
- Vicente Garay 
- Luna Garcés 

## Instrucciones

> [!NOTE]
> Si llega a haber un error de conexión, puede ser debido a que se actualizo la base de datos, por favor contactar a Vicente.garay@uc.cl para activarla nuevamente.

> Para ejecutar este notebook, necesitarás tener instalado lo siguiente:
> *   PySpark
> *   Neo4j
> *   Pandas

### Parte 1

Análisis de grafos mediante PySpark. 

El código incluye los pasos para configurar el entorno, cargar los datos, aplicar funciones de mapeo y reduce, para luego detectar triángulos en el grafo. 

Para llevar la tarea a cabo se utilizan las siguientes librerías 


### Parte 2

Se utilizó la siguente base de datos 
    
    ```
@MISC{konect:2017:opsahl-usairport,
    title = {US airports network dataset -- {KONECT}},
    month = oct,
    year = {2017},
    url = {http://konect.cc/networks/opsahl-usairport}
}

```

Esta base de datos contiene información sobre los vuelos entre aeropuertos en Estados Unidos. 
Se trata de un grafo direccionado y los pesos significan la cantidad de vuelos entre dos aeropuertos.


