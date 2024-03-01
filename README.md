# Proyecto_linea_144


Quiero compartir mi primer proyecto **"end to end"** en el campo del análisis de datos. Como aspirante a Data Analyst, he tenido la oportunidad de trabajar en un proyecto significativo y quiero contarles sobre él


## **Objetivo:** 


Este trabajo nace de la inquietud de conocer en profundidad las causas de la violencia por motivos Género en la República Argentina a través de los datos aportados por los llamados a la línea 144, por lo tanto el carácter de la presente indagación es *exploratorio*. Aún así, el camino transitado ha estado guiado por diversas hipótesis y con objetivos claros.

Como *objetivo de carácter general* puedo indicar que la mirada ha estado dirigida a:

- Conocer las principales características sociales y demográficas de las personas que acuden mediante llamados gratuitos a la línea 144 para trazar similitudes y regularidades entre las personas usuarias del servicio para poder acceder a la problemática de genero a través de datos certeros que contribuyan a dilucidar líneas de acción para intervenir sobre la problemática. 


## Datos utilizados

Para realizar este trabajo he utilizado datos reales, que fueron extraídos de fuentes oficiales del Gobierno de la República Argentina. 

La exploración de datos a partir del algorítmo *K-means* ha sido creado a partir del dataset
- Linea144-enero-diciembre-2022.csv [extraído de](https://www.datos.gob.ar/dataset/generos-base-datos-linea-144/archivo/generos_1.3)

La visualización que he realizado en un paso posterior, he querido complejizarla para dar un carácter relacional y de mayor profundidad a la explicación del fenómeno analizado. Es por ello que he adicionado otros dataset que han sido extraídos del portal de Datos abiertos de la República Argentina, sin embargo también he construido mis propios CSV con información faltante pero que también ha sido publicado por sitios oficiales:

**CSV de Construcción Propia** :construction_worker:

- Poblacion_total_por_sexo_provincia_2010.csv fue construido con [información de INDEC sobre el último censo registrado en el país](https://www.ign.gob.ar/NuestrasActividades/Geografia/DatosArgentina/Poblacion2)
- Salario-minimo-2022.csv fue construido con [información extraída de internet](https://datosmacro.expansion.com/smi/argentina)

**CSV oficiales** :office:
- Linea144-enero-diciembre-2022.csv extraído de [aquí](https://www.datos.gob.ar/dataset/generos-base-datos-linea-144/archivo/generos_1.3)
- Tasa-desocupación-jefas-mujeres-hogares-urbanos.csv extraído de [aquí](https://www.datos.gob.ar/dataset/obras-actividad-economica-empleo-pobreza---mercado-trabajo/archivo/obras_13.9)
- Tasa-desempleo-18a65.csv extraído de [aquí](https://www.datos.gob.ar/dataset/obras-actividad-economica-empleo-pobreza---mercado-trabajo/archivo/obras_13.8)
- Percentiles_mujer_total_total.csv extraído de [aquí](https://www.datos.gob.ar/dataset/produccion-percentiles-salarios-por-genero-actividad/archivo/produccion_8b431ad8-4d2d-4003-a8d7-6cd5280569d3)


## Resúmen del Trabajo realizado

🔍 **Explorando el Comportamiento de los Llamados a la Línea 144:** Mi proyecto se centró en analizar un dataset que contenía llamados a la línea 144 de Argentina, que brinda asistencia a víctimas de Violencia de Género. A pesar de no tener experiencia laboral, me propuse entender los datos desde diferentes ángulos.

📊 **K-means para la Clusterización:** Comencé aplicando el algoritmo de clusterización K-means para identificar patrones en los llamados. Esta técnica me permitió agrupar los datos en categorías relevantes, lo que arrojó luz sobre diferentes tipos de situaciones. Se puede acceder a este trabajo a partir del archivo creado para tal fin en [Kaggle](https://www.kaggle.com/code/animonte/proyecto-genero-linea144)

📈 **Visualización Impactante en Power BI:** Luego, me propuse analizar los datos de la Línea 144 a la luz de datos macroeconómicos para analizar relaciones entre pobreza junto a indicadores desempleo y aumento de casos de violencia. Las visualizaciones no solo hicieron que los datos fueran más accesibles, sino que también ayudaron a identificar tendencias y momentos clave. El resultado obtenido puede visitarse desde el archivo que está dentro de este [respositorio](https://github.com/animonte/Proyecto_linea_144/blob/main/proyecto-genero-linea144.pbix), pero aquí les dejo la vista previa a través de imágenes:

- Descripción general de los llamados en 2022:

<img width="900" alt="Screenshot 2023-08-06 at 21 12 03" src="https://github.com/animonte/Proyecto_linea_144/assets/125661622/a6280a99-d016-476f-b893-c6615e0dbc2d">


- Descripción de situación por provincias:

<img width="900" alt="Screenshot 2023-08-06 at 21 12 19" src="https://github.com/animonte/Proyecto_linea_144/assets/125661622/967a240a-2c87-4a56-a7de-8e26eee0c798">


- Análisis relacional con aspectos macroeconómicos:

<img width="900" alt="Screenshot 2023-08-06 at 21 12 30" src="https://github.com/animonte/Proyecto_linea_144/assets/125661622/a62878c9-de0c-4e6b-90eb-987dbc02bb89">



📑 **Informe de Resultados:** Finalmente, redacté un informe detallado que describe mi análisis paso a paso. Quise asegurarme de que cualquier persona pudiera entender los hallazgos y su importancia. Pueden acceder a él desde el siguiente [archivo](https://github.com/animonte/Proyecto_linea_144/blob/main/Informe%20de%20resultados.%20L%C3%ADnea%20144%20.pages)



## 🙌 **Reflexión y Aprendizaje:** 

Este proyecto no solo me permitió aplicar mis habilidades técnicas, sino que también me sensibilizó sobre un tema crucial. Aprendí que los datos pueden tener un impacto real en la sociedad y estoy emocionada por seguir contribuyendo de esta manera.


