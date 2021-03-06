
# Práctica I

Práctica 1 de la asignatura de Tipólogía y ciclo de vida de los datos, primer semestre de 2022. 

En esta práctica se elabora un caso práctico orientado a aprender a identificar los datos relevantes para un proyecto analítico y usar herramientas de extracción de datos.


## Componentes de la práctica

 - Jonás Medina Brito (jmedinabrit@uoc.edu)
 - Miguel Rafael Esteban Martín (mestebanmart@uoc.edu)
 
## Guía  de la práctica

La guía de la práctica se encuentra en la siguiente ruta:

 - [**`doc/doc-pract-1.pdf`**](doc/doc-pract-1.pdf). Los fuentes de este documento es el notebook de jupyter [`notebook/doc-pract-1.ipynb`](notebook/doc-pract-1.ipynb)

## Descripción de los ficheros fuente

La extración como para el proceso y curación de los datos, así como su representación se ha realizado gracias a un notebook de [jupyter](https://jupyter.org/)

Con respecto a como ejecutar el notebook utilizando [docker](https://www.docker.com/), se puede consultar en este [documento](doc/install/docker.md)

El notebook con el código se encuentra en el directorio

 - [`notebook/pract-1.ipynb`](notebook/pract-1.ipynb)
 
 Los dataset que se han utilizado para crear el dataset principal se localizan en el directorio [`subdataset`](./subdataset)
 
 - [`subdataset/data_gas_prices_household_consumers.csv`](subdataset/data_gas_prices_household_consumers.csv) Precios del gas (Euro/kWh) para consumidores domésticos.
 - [`subdataset/data_gas_prices_no_household_consumers.csv`](subdataset/data_gas_prices_no_household_consumers.csv) Precios del gas (Euro/kWh) para empresas. 
 - [`subdataset/data_electricity_prices_household_consumers.csv`](subdataset/data_electricity_prices_household_consumers.csv): Precio de la electricidad (Euro/kWh) de los países europeos para consumidores domésticos para la banda de consumo entre  2.500 a 4.999 kWh 
 - [`subdataset/data_electricity_prices_no_household_consumers.csv`](subdataset/data_electricity_prices_no_household_consumers.csv): Precio de la electricidad  (Euro/kWh) de los países europeos para empresas para la banda de consumo de menos de 20 MWh. 
 
 ### Dataset 
 
 La exportación del dataset principal se localiza en la ruta  [`dataset/energy_price_dataset.csv`](./dataset/energy_price_dataset.csv)

 
## DOI del dataset en Zenodo

DOI: **`10.5281/zenodo.6424152`**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6424152.svg)](https://doi.org/10.5281/zenodo.6424152)






