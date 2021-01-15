# Minería de datos: Modelo para la predicción del éxito de películas
Este repositorio es un proyecto de minería de datos, cuyo objetivo será tener un sistema que nos ayudará a predecir si una película que todavía que no ha salido podría ser exitosa o no, y si es recomendable.

1. [ Descripción de archivos ](#desc)
2. [ Tecnologías utilizadas ](#usage)
3. [ Estructura del proyecto ](#structure)


<a name="desc"></a>
### **Descripción de archivos**

* [1_Preproceso.ipynb](1_Preproceso.ipynb): en este notebook se hará el preproceso de cada columna y se desecharán aquellas que no serán consideradas para nuestro modelo.
* [2_Transformation.ipynb](2_Transformation.ipynb): la labor de este notebook será la de transformar algunos datos de columnas, los cuales no pueden ser tratados por un algoritmo de Machine Learning.
* [3_Mineria.ipynb](3_Mineria.ipynb)_: en dicho notebook se llevará a cabo la labor de minería de los datos preprocesados y transformados, con el objetivo de obtener la predicción de la valoración media y benificio.
* [movies_metadata.csv](movies_dataset/movies_dataset.csv): este es el dataset original que será utilizado para la creación del modelo.
* [movies_training.csv](movies_dataset/preprocessed_training.csv): datos obtenidos a través del preprocesado del dataset original y los cuales contienen, todos y cada uno de ellos, la columna de revenue. Este dataset, por lo tanto será utilizado para el entrenamiento del modelo.
* [movies_testing.csv](movies_dataset/preprocessed_testing.csv): datos obtenidos a través del preprocesado del dataset original y los cuales no contienen revenue, lo cual será útil para el testing.

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
    * Exportación de dataos preprocesados

2. Transformación
    * Importando paquetes y datasets
    * Transformación de lenguaje natural
        * Transformación de los datos de training
        * Transformación de los datos de testing
    * Transformación de columnas categóricas
        * Release day of the week
        * Original language


## Autores

* **Raúl Bernalte** - [raulbs7](https://github.com/raulbs7)
* **Hector Moreno**  - [hectorms86](https://github.com/hectorms86)
* **Guillermo Bautista** - [Lhions](https://github.com/Lhions)
* **David Moreno** - [david09mc](https://github.com/david09mc)

