# Minería de datos: Modelo para la predicción del éxito de películas
Este repositorio es un proyecto de minería de datos, cuyo objetivo será tener un sistema que nos ayudará a predecir si una película que todavía que no ha salido podría ser exitosa o no, y si es recomendable.

1. [ Descripción de archivos ](#desc)
2. [ Tecnologías utilizadas ](#usage)
3. [ Estructura del proyecto ](#structure)


<a name="desc"></a>
### **Descripción de archivos**

* [1_Preproceso.ipynb](1_Preproceso.ipynb): en este notebook se hará el preproceso de cada columna y se desecharán aquellas que no serán consideradas para nuestro modelo.
* [movies_metadata.csv](movies_dataset/movies_dataset.csv): este es el dataset original que será utilizado para la creación del modelo.
* [movies_training.csv](res/movies_training.csv): datos obtenidos a través del preprocesado del dataset original y los cuales contienen, todos y cada uno de ellos, la columna de revenue. Este dataset, por lo tanto será utilizado para el entrenamiento del modelo.
* [movies_testing.csv](res/movies_testing.csv): datos obtenidos a través del preprocesado del dataset original y los cuales no contienen revenue, lo cual será útil para el testing.

<a name="usage"></a>
### **Tecnologías usadas**

* [scikit-learn](https://scikit-learn.org/stable/index.html)
* [seaborn](https://seaborn.pydata.org)
* [matplotlib](https://matplotlib.org)
* [scipy](https://www.scipy.org)
* [pandas](https://pandas.pydata.org)
* [numpy](https://numpy.org)

<a name="structure"></a>
### **Estructuras del proyecto**

1. PREPROCESO
    * Imports y carga de dataset
    * Eliminación de columnas no usadas
    * Procesamiento de columnas
        * Adult
        * Title
        * Tagline
        * Overview
        * Vote count
        * Vote average
        * Release date
        * Runtime
        * Original language
        * Genre
        * Production companies
        * Production countries
        * Revenue
    * Saving processed datasets


## Autores

* **Raúl Bernalte** - [raulbs7](https://github.com/raulbs7)
* **Hector Moreno**  - [hectorms86](https://github.com/hectorms86)
* **Guillermo Bautista** - [Lhions](https://github.com/Lhions)
* **David Moreno** - [david09mc](https://github.com/david09mc)

