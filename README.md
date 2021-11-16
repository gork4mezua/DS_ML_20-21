# Machine Learning - Master Ciencia de Datos
Repositorio para almacenar los datos y el código (modelos, dataset, etc.) relacionados con las distintas prácticas a realizar en la asignatura de *Machine Learning* del Máster Universitario de Ciencia de Datos. En la siguiente tabla, se muestra una breve descripción del contenido que ofrecen los distintos directorios del repositorio.

| Directorio | Descripción |
| ----------- | ----------- |
| base | Este directorio contiene los projectos de Weka (ficheros .arff) con el preprocesamiento realizado. |
| data | Este directorio contiene los datos utilizados para la realización de la práctica, es decir, el dataset. |
| base | Este directorio contiene los modelos utilizados para la segunda práctica de la asignatura: clasificadores probabilísticos. |

## Directorio base
Como se ha dicho, este directorio recoge ficheros '.arff', es decir, projectos de Weka. Estos son los ficheros almacenados:
- **CommonBase**: Projecto que tiene cargado el dataset de las setas y se le ha aplicado el preprocesamiento (eliminar valores ausentes, eliminar attributos innecesarios, etc.).
- **NumericBase**: Se ha realizado lo mismo que en el fichero 'CommonBase.arff', pero adicionalmente se han convertido todas las clases nominales a numéricas. Esta base se ha utilizado para poder trabajar con modelos como el LDA (Linear Discriminant Analysis) y QDA (Quadratic Discriminant Analysis).
## Directorio practica2
Dentro de este directorio, hay otro que se llama 'models'. Dentro de este último directorio se encuentran los distintos modelos generados a lo largo de la práctica, cada uno con el nombre del método correspondiente (LDA, QDA, etc.). Los primeros que aparecen son los generados mediante todas las variables. Si se quiere acceder a los modelos con los diferentes métodos de filtrado aplicados, se debe acceder al directorio 'FSS' que se encuentra en el mismo sitio y ahí se pueden encontrar separados en subdirectorios los distintos modelos. Cada subdirectorio tiene el nombre del FSS aplicado (univariant, multivariant, wrapper).