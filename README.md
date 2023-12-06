# DA_BA_Project2
------------------------------------------
En este proyecto de Data Analitics, se procesan y analizan una serie de datos respecto a los accidentes viales en la Ciudad Autonoma de Buenos Aires, con el objetivo de crear conciencia situacional del lugar en que esta la Ciudad Autonoma de Buenos Aires con respecto a los accidentes viales y verificar las tendencias de estas para crear politicas de prevencion de este tipo de accidente.

## Coleccion de datos y EDA 
------------------------------------------
El primer paso para la consecucion de este proyecto es la recoleccion de todos los datos pertinentes en el sitio web de la gobernacion de la ciudad autonoma de buenos aires: https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales para obtener un dataset lo mas completo posible y realizar un analisis exploratorio de datos (EDA) que nos de una perspectiva de la calidad e integridad del dataset, a partir de ella obtener la informacion relevante para los proximos pasos del proyecto, que son el procesamiento del dataset y la creacion de un dashboard interactivo que entregara en un formato, claro y consiso la situacion general de los accidentes viales en CABA, las tendencias, los patrones y informaciones criticas, el registro detallado del proceso de EDA de encuentra en el archivo **EDA.ipynb** en el repositorio. 

## ETL primera parte 
------------------------------------------
Despues del proceso de EDA que nos da una idea de la composicion, la consistencia, completitud y el tipo de datos del dataset, procedemos a limpiar y normalizar el dataset principal cargandolo desde un archivo excel a un dataframe, a partir de este se limpian y normalizan los datos que seran usados en la construccion del dashboard conteniendo las metricas y KPIs relevantes para el analisis de la situacion vial, el detalle del proceso de limpieza y normalizacion esta en el archivo **ETL.ipynb** en el repositorio.

## ETL segunda parte
------------------------------------------
En la segunda parte se cargan el dataset ya normalizado para la creacion de varios dataframes conteniendo la informacion necesaria para construir los KPIs y metricas necesarias para el dashboard final, la presentacion de los datos cada dataframe toma la informacion del DF principal y lo reorganiza para que contenga la informacion ya procesada de los diferentes objetos visuales de POWER BI donde sera realizado el dashboard final, estos dataframes son cargados como pestañas de un archivos excel que sera utilizado como fuente de informacion en el editor de POWER BI, el detalle de el proceso de ETL final esta en el archivo **ETL_Parte_2.ipynb** en el repositorio.

## Data analysis Dashboard 
------------------------------------------
Finalmente con la informacion procesada en los anteriores pasos, se crea el dashboard final con 2 KPIs principales, la cantidad de victimas de accidentes viales por semestre, la cantidad por cada 100000 habitantes, la tendencia comparada con el año anterior, y la cantidad de accidentes viales con motocicletas por año, junto con la tendencia comparada con el año anterior, ademas de las metricas de meses, comunas, presuntos causantes y calles con mas accidentes en la Ciudad Autonoma de Buenos Aires, para obtener una vision mas clara de la situacion vial de la ciudad, el dashboard se encuentra en el repositorio en el archivo **"Homicidios_viales_caba"**    
