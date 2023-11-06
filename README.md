# Proyecto: Segmentacion-de-videos-de-Tik-Tok

## Objetivo del trabajo: 
### Encontrar patrones en los datos de videos de Tik Tok que pueden ayudarnos a analizarlos de manera más efectiva utilizando K-Means

En este proyecto, utilizaremos una técnica de aprendizaje automático no supervisada para el agrupamiento de los datos.
K-means es una de las formas más populares de agrupamiento a partir de la cual intentaresmos encontrar patrones en los datos.

## Datos
Usaremos el archivo 'tik_tok3.csv' que es el conjunto de datos correspondiente al output de la etapa de limpieza y EDA realizada previamente sobre un dataset de Tik Tok. 

## Etapas
* Importar dataset
* Análisis de las variables
* Modelado con K Means:
    Escalar datos |
    Seleccionar variables para el modelo |
    Método del codo |
    Instanciar el modelo |
    Interpretación del modelo |
    Evaluación del modelo
	
## Participantes Grupo 3:
Escalante Virginia
Ordinola Rocío
Panei Julia


## Diccionario de conceptos: 

| Variable | Definición |
| --------- | --------- |
|ID | Número identificatorio de cada registro ingresado |
| estado_reclamo | Separa los estados en opinión o reclamo |
| ID_video | Número que identifica cada video |
| duracion_video_seg | Tiempo de duración expresado en segundos |
| transcripcion_video | Transcripcion de lo que encuentra en el video |
| estado_verificado | Se encuentra verificado o no verificado |
| estado_bloqueo_autor | Estado del autor del video: bloqueado, activo o bajo revisión |
| vistas_video | Número total de vistas |
| likes_video | Número total de likes |
| share_video | Número total de shares (veces que se comparte el video) |
| descargas_video | Número total de descargas |
| comentarios_video | Número total de comentarios |
| largo_de_texto |  Cantidad de caracteres de la transcripcion de lo que encuentra en el video. Es igual a 0 cuando son menos de 60 caracteres y es igual a 1 cuando es mayor o igual a 60 |
