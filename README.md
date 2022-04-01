# Práctica I

Práctica 1. En esta práctica se elabora un caso práctico orientado a aprender a identificar los datos relevantes para un proyecto analítico y usar herramientas de extracción de datos.


## Arranque del docker

Para esta práctica se usa una imagen de docker para data science `jupyter/scipy-notebook`  Para arrancar el docker se utiliza la utilidad `docker-compose`. Para arrancar:

```[shell]

# docker-compose up

```

Después del arranque por consola ofrece una ruta del tipo `http://9f6f26c2d0e3:8888/lab?token=e2c874bc5027f5841441fda4dc8fd7081393bdf1792491fb`



## Ejemplo de petición custom

```[shell]
$ curl   'https://ec.europa.eu/eurostat/databrowser-backend/api/extraction/1.0/LIVE/false/tsv/<clave_data_set>?i'  | gunzip -

```

Donde:
 - `clave_data_set` es el identificador del dataset. Ejemplo `NRG_PC_204_C__custom_2388428` 




