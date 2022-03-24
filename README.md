# ML_Mercado_Inmobiliario

Este es un proyecto donde se usando los datos de https://blog.properati.com/properati-data/# se hacen analisis y predicciones del mercado inmobiliario argentino. Principalmente se usan modelos de machine learning para predecir, dependiendo de las caracteristicas de un inmueble, cual sera su precio. El notebook de jupyter contiene todo el proceso desde la limpieza, analisis y creacion de modelos, comentados debidamente para hacer claro el proceso. Ademas de predecir el precio de las propiedades tambien, a travez del proyecto, encontramos interesantes insights sobre el mercado inmobiliario argentino.

Las principales librerias que usamos son pandas, numpy, scipy para manipulacion de los datos. Usamos seaborn y matplot para visualizar las distribuciones de los datos y resultados de los modelos, entre otros. Para la construccion de los diferentes modelos de machine learning usamos principalmente la libreria de sklearn. Otras librerias de soporte que se usaron se encuentran en el archivo 'requirements.txt' de este repositorio.

En las primeras partes del proyecto se hace una limpieza de los datos faltantes y erroneos del dataset. Tambien se hace una imputacion de valores faltantes en los casos que se consideró necesario. Eliminamos asi mismo outliers del data set que pudieran crear un mal desempeño en los modelos de ml.

En la segunda parte del proyecto creamos y probamos la efectividad de algunos modelos de ml para predecir el precio de una propiedad dependiendo de las caracteristicas mas importantes del data set. Se usaron modelos de Random Forest y Regresion lineal con atributos polinomicos.

Para mejorar el desempeño de los modelos se aplicaron tecnicas de optimizacion de parametos como Random Search y Grid Search, asi como diferentes transformaciones de los atributos del data set (creacion de parametros polinomicos)

