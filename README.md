# Análisis de ConnectaTel

Este proyecto forma parte del Sprint 7. El objetivo fue analizar cómo utilizan los clientes de ConnectaTel los servicios de llamadas y mensajes, además de identificar valores atípicos y crear grupos de usuarios según su edad y nivel de uso.

## Datos utilizados

El análisis se realizó con tres archivos:

- `plans.csv`: contiene la información de los planes Básico y Premium.
- `users_latam.csv`: incluye los datos de los clientes, como edad, ciudad, fecha de registro y plan contratado.
- `usage.csv`: contiene los registros de llamadas y mensajes realizados por los usuarios.

## Etapas del análisis

Durante el proyecto se realizaron los siguientes pasos:

1. Carga y exploración inicial de los datasets.
2. Revisión de valores nulos, sentinels y fechas fuera de rango.
3. Limpieza y corrección de los datos encontrados.
4. Creación de un resumen de llamadas, mensajes y minutos por usuario.
5. Elaboración de histogramas y boxplots.
6. Identificación de valores atípicos mediante el método IQR.
7. Segmentación de clientes por edad y nivel de uso.
8. Redacción de conclusiones y recomendaciones para el negocio.

## Herramientas utilizadas

- Python
- pandas
- NumPy
- seaborn
- matplotlib
- Jupyter Notebook

## Cómo ejecutar el notebook

1. Descarga el notebook y los tres archivos CSV.
2. Abre el archivo `.ipynb` en Jupyter Notebook o Google Colab.
3. Coloca los datasets en la ubicación indicada en las celdas de carga.
4. Ejecuta las celdas en orden desde el inicio.

En el entorno del curso, los archivos se leen desde la carpeta `/datasets`. Si el notebook se ejecuta en otro entorno, como Google Colab, es necesario subir los CSV y ajustar las rutas de lectura según su ubicación.

## Resultado general

El análisis permitió observar que la mayor parte de los clientes pertenece al grupo de uso medio. También se encontraron algunos valores atípicos en mensajes, llamadas y minutos de llamada; se conservaron porque representan consumos posibles y pueden ayudar a identificar clientes con necesidades diferentes.
