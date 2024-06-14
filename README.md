# Matemáticas para Data Science

En este repositorio podrás  encontrar una serie de notebooks con apuntes sobre matemáticas, estadística y probabilidad.

**Contenido del repositorio**

- Folders: Cada folder representa un área específica de estudio, ó un curso (principalmente [Platzi](www.platzi.com)).
- imgs: Folder con imágenes. Esta carpeta está dentro del folder principal del curso o área.
- notebooks: Archivos `ipynb` con temas específicos, en algunas ocasiones puede contener apuntes de una o varias clases dependiendo el curso al que corresponda.

## ✋ Antes de empezar
1. Crear la carpeta `data` en la raíz del proyecto
2. Descargar los datasets utilizados en los notebooks y colocalos en la carpeta `data` previamente creada.
3. Renombrar los archivos con el nombre que está en el código.
4. Para el ejercicio de [Distribución continua](./probabilidad/distribucion_continua.ipynb) es necesario instalar la dependencia `xlrd` en el entorno virtual de tu preferencia, en mi caso yo lo hice con anaconda :snake:.
      ```bash
      consda install xlrd=2.0.1
      ```

| Link de descarga | Renombrar a | Se utiliza en |
| --- | --- | --- |
| [cars](https://www.kaggle.com/datasets/lepchenkov/usedcarscatalog) | cars | [Tipos de datos](./estadistica_descriptiva/tipos_de_datos.ipynb), [Medidas de tendencia central](./estadistica_descriptiva/medidas_centrla.ipynb), [Medidas de dispersión](./estadistica_descriptiva/medidas_dispersion.ipynb), <br>[Procesamiento de datos numéricos](./estadistica_descriptiva/procesamiento-datos-numericos.ipynb), [Procesamiento de datos categóricos](./estadistica_descriptiva/procesamiento-datos-categoricos.ipynb) |
| [s057](https://seattlecentral.edu/qelp/sets/057/057.html) | s057 | [Distribución continua](./probabilidad/distribucion_continua.ipynb)
| [economia-y-turismo-en-el-centro-historico](https://datos.cdmx.gob.mx/dataset/economia-y-turismo-en-el-centro-historico) | econdata | [Funciones de muestreo](./estadistica_inferencial/01_funciones_muestreo.ipynb) |


Cualquier feedback o contribución es bien recibida.


<h3 align="center"> Made with 💜 by Paho </h3>