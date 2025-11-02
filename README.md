# 🖼️ Proyecto 4: Power BI - GRUPO 1 - LA BANDA DEL LIENZO

Por Elena Jiménez, María Nicolás e Irina Ostojic

## 🎨 Descripción del proyecto

__La Banda del Lienzo__ es un análisis de datos desarrollado en Power BI que explora la representación de mujeres artistas en tres de los museos más reconocidos del mundo:
el Isabella Stewart Gardner Museum (Boston), el Metropolitan Museum of Art (Nueva York) y el Museum of Modern Art - MoMA (Nueva York). Una pregunta resuena en cada gráfico, en cada colección:

_¿Dónde están las mujeres en el arte?_ 

## 📊 Metodología

El análisis parte de datasets obtenidos en Kaggle de los tres museos mencionados.

Etapas del análisis:

1. Limpieza y depuración de datos (Python / Power BI)

2. Análisis exploratorio de artistas y obras

3. Creación de dashboards interactivos en Power BI que muestran la brecha de género, evolución temporal de adquisiciones y top de artistas por museo.

4. Lectura e interpretación crítica de los resultados

5. Construcción simbólica de la Sala 404 como conclusión colectiva


## 📁 Estructura del repositorio

El repositorio se organiza en cinco componentes principales, que reflejan el flujo completo del trabajo: desde la obtención de datos hasta la visualización final en Power BI.

- moma.csv                              # Dataset bruto MoMA
- artists-moma.csv                      # Dataset bruto MoMA artistas
- artwork-moma.csv                      # Dataset bruto MoMA obras
- janson.csv                            # Dataset bruto MET 
- gardner.csv                           # Dataset bruto Gardner

- EDA-moma.ipynb                        # EDA y limpieza del dataset del MoMA
- EDA_Gardner.ipynb                     # EDA y limpieza del dataset del Gardner
- EDA_Janson.ipynb                      # EDA y limpieza del dataset del MET

- df_gardner_clean.csv                  # Dataset tratado Gardner
- df_janson_clean.csv                   # Dataset tratado MET
- df_moma_clean.csv                     # Dataset tratado MoMA  
- Ubi.csv                               # Excel con ubicaciones para mapa

- SALA404_final.pbix                    # Archivo de Power BI con los dashboards finales

- README.md                             # Este documento

## 🛠️ Herramientas utilizadas

- Python / Pandas / Regex / Matplotlib / Seaborn – Limpieza y preprocesamiento de los datasets

- Power BI – Visualización interactiva y creación de dashboards

- Excel – Soporte en la organización y verificación de datos

- Google Docs – Redacción y presentación narrativa del proyecto

## 🧠 Conclusiones

- La desigualdad en la representación de mujeres artistas no es un hecho del pasado, sino un fenómeno persistente en las instituciones culturales.

- Los datos evidencian la necesidad urgente de revisar políticas de adquisición y exhibición para lograr una mayor equidad.

- El 9,84% de participación femenina no representa únicamente un dato estadístico, sino un indicador de una necesidad urgente de cambio por parte de las instituciones. 

- Promover la equidad de género con la adquisición y exhibición de obras femeninas es fundamental para construir museos más representativos, plurales y comprometidos con la igualdad.