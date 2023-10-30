Este repositorio contiene tres directorios en los que podremos encontrar:

Enlace a github para dashboard: https://github.com/TRASH-NET/dashboard_DST.git

1.)

dashboard: En este directorio se encuentra el dashboard con su respectivo documento que indica las dependencias necesarias
para poder ejecutar el servidor. para esto se deben correr los siguientes comandos. Ademas, podemos encontrar la muestra con 1500 
extraida del dataset que se encuentra en el directorio data.

pip install -r requirements.txt 

posteriormente instaladas las dependencias se requiere usar el siguiente comando para iniciar el servidor:


streamlit run dashboard.py


2.) 

data: En este directorio se encuentra el dataset que uso para realizar este dashboard y extraer la muestra.

3.) 

logic: En este directorio se encuentra el archivo con extension.qmd donde se evidencia el proceso de adecuacion del dataset,
extraccion de la muestra, y calculo de intervalos de confianza para proporcion y media de variables que se encuentran dentro
del dataset. 
    -Para visualizar este documento en forma de presentacion con extension .html se debe abrir el archivo dataStoryTelling2.html 
    -El codigo fuente se encuentra en el archivo con extension .qmd llamado dataStoryTelling2.qmd
    -El dataset adecuado se encuentra en formato  xlsx llamado DataClear.xlsx

