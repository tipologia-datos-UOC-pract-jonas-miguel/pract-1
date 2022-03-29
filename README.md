# Práctica I

Práctica 1. En esta práctica se elabora un caso práctico orientado a aprender a identificar los datos relevantes para un proyecto analítico y usar herramientas de extracción de datos.

## Ejemplo de petición

```
curl 'https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/<clave_data_set>$DEFAULTVIEW/?format=TSV&compressed=false' 

```

Donde:
 - `clave_data_set` es el identificador del dataset. Ejemplo `NRG_PC_202_C` corresponde a (Gas prices components for household consumers - annual data
)|[https://ec.europa.eu/eurostat/databrowser/view/nrg_pc_202_c/default/table?lang=en]


