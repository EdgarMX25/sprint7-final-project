# Analisis ConnectaTel
## Objetivo:
Poner en practica lo aprendido en el analisis de datos, usando las herramientas vistas durante el sprint 7, como matplotlib, pandas,seaborn y numpy, para lo cual se realizo el analisis de **comportamiento de los clientes** de la empresa de telecomunicaciones ConnectaTel. La información comprende hasta el año 2024, lo que permite analizar el comportamiento del negocio para ese periodo de tiempo.

Para este proyecto se utilizar los dataset de la empresa ConnectaTel:
- plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
- users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
- usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

## Etapas:

- Se inicio con un analisis de las columnas de cada dataset, encontrando campos claves que permiten asociar los tres datasets (user_id, plan)
- Se realizo la limpieza de datos, cambiando datos errones por la mediana (age), eliminando información de fechas que aun no han trasncurrido.
- Se analizo la información en busca de datos atipicos.
- Se unificaron los dataset *usage* y *users*
- Se clasifico la infomación generando nuevos campos para poder segmentar por categoras de edad y uso (cantidad de llamadas y mensajes)
- Se generaron las grafias (histogramas y boxplot) para un mejor analisis de la información.

## Ejecución del Notebook:

