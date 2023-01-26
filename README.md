# <h1 align=center> ** Proyecto Individual Nro.2 - DATA06 ** </h1>
# <h1 align=center>**`Data Scientist Jr`**</h1> 

# <h1 align=center> Mateo Murillo </h1>

![img1](https://user-images.githubusercontent.com/111402986/213601046-e633611a-66cf-404a-aa78-35dd23a7f65b.png)
 
<h1 align=center> ¡Bienvenidos a mi segundo proyecto individual de la etapa de labs! </h1>

## **Introducción**

Durante el presente proyecto se desarrollará un proceso de machine learning de regresión logistica, el cual abarcará el proceso de recolección, preparación e implementación de un modelo de clasificación, con el objetivo de poner a prueba su capacidad de ejecución y predicción.

## **Recolección y preparación**

En esta parte del proyecto debiamos de cargar la data predispuesta en formato .parquet, debido a esto tuve que instalar ***`Pyarrow`***, el cual funcionaria como motor de procesamiento de este tipo de archivos, posteriormente con Pandas crearimos dos dataframe con la respectiva info del contenido.

![librerias](https://user-images.githubusercontent.com/111402986/214753899-66d2dc8f-7f9a-4444-af08-66ddebc58a90.png)

![image](https://user-images.githubusercontent.com/111402986/214753969-63321789-a21c-4f81-a7ce-1eae9c705bf8.png)

Aparte de la adquisión de la data, también debia de ser preparada para usar el algoritmo de regresión logistica:

![image](https://user-images.githubusercontent.com/111402986/214754149-aec767f5-e045-4230-a3ce-b08f88d3030e.png)

![image](https://user-images.githubusercontent.com/111402986/214754210-043a8ac6-00f9-4ed3-bc99-8dc66bc841e7.png)

![image](https://user-images.githubusercontent.com/111402986/214754239-20de2403-8693-4cce-8fa2-89feaea2ac21.png)

## **Entendiendo la data**

Para la resolución de este apartado, realizamos un EDA más detallado y además encontramos las respectivas correlaciones e indices para aplicar en el modelo

![image](https://user-images.githubusercontent.com/111402986/214754471-4cc1473e-e13d-4259-9079-eed7d274677f.png)

## **Entrenamiento de la data y pruebas**

Aqui utilizaré el algoritmo de regresión logistica, ademas de incorporar metricas de evaluación sobre el modelo y otras herramientas que prueben el nivel de predicción

![image](https://user-images.githubusercontent.com/111402986/214754702-bfc2e713-d623-44fd-a473-34ca26630a2c.png)

![image](https://user-images.githubusercontent.com/111402986/214754780-7d4441e1-342c-41f8-83c0-a988f1eafaa3.png)

## **Exportaccion y EXTRAS**

Finalmente, exportaria el modelo en un formato de archivo csv y como adición realizo un preprocesamiento de outliyer e incorporta hiperparametrización al modelo con el objetivo de mejorarlo:

![image](https://user-images.githubusercontent.com/111402986/214755248-08efb429-3f23-4741-a1e9-ceb66756ba6e.png)

![image](https://user-images.githubusercontent.com/111402986/214755292-a19c26a6-e4e4-43cb-ba34-fbbb44cde86b.png)
