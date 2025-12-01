# P2-Procesamiento-Limpieza-Python-Ruben
## Análisis y limpieza de ventas de videojuegos (1980-2020)
Este proyecto consiste en la **limpieza, análisis** de un dataset de ventas de videojuegos, con el objetivo de explorar patrones de mercado, regiones mas relevantes y distribución de ventas por género,plataforma y compañia.

El dataset original es de una fuente pública: (https://www.kaggle.com/datasets/kedokedokedo/vgsales).

## Explicación breve sobre el dataset
| Columna | Descripción | 
|---|---|
| Título | Nombre del videojuego |
| Plataforma | Consola donde se lanzó |
| Año de lanzamiento | Año de salida del videojuego |
| Género | Categoría del videojuego |
| Compañía | Distribuidora del videojuego |
| Ventas totales (M) | Ventas mundiales en millones de copias |
| Ventas en NA (M) | Ventas en Norteamérica en millones |
| Ventas en UE (M) | Ventas en Europa en millones |
| Ventas en JP (M) | Ventas en Japón en millones |
| Ventas en otras localizaciones (M) | Ventas en otras localizaciones en millones |

## Carga y preparación del dataset
Importación de librerías: ```import pandas numpy seaborn matplotlib.pyplot missigno```
Carga del DataFrame para posterior transformación y análisis.

## Análisis previo
- Visualización de datos.
- Información general del DataFrame.
- Visualización de datos faltantes.
- Análisis de outliers.
- Identificación de datos duplicados.
  
## Tratamiento de datos y limpieza
- Cambio de datos.
- Eliminación de filas.
- Normalización de textos.
- Creación de columnas derivadas.

## Análisis generales
- Top 20 de juegos vendidos entre 1980 y 2020.
- Gráfico de tendencias del total videojuegos vendidos por año.
- Ventas totales agrupadas por región
- Consolas más populares por región
- Géneros más vendidos por región

## Conclusiones
- Los títulos más vendidos pertenecen en su mayoría a Nintendo, Wii y PS2.
- El género de Acción es el más abundante, pero Shooter y Sports destacan en ventas.
- Norteamérica y Europa concentran la mayor parte del mercado.
- Japón presenta un comportamiento distinto, priorizando otras categorías.
- El periodo con más ventas totales se sitúa entre 2006 y 2010.
- Las tendencias de ventas varían fuertemente según plataforma y compañía.

## Uso del proyecto
### Requisitos
- Librerias: ```pip install pandas numpy matplotlib seaborn missingno```
### Pasos
- Clonar repositorio : ```git clone https://github.com/tuusuario/P1-Analisis-Datos-Excel-Ruben.git```
- Abrir archivo ```.ipynb``` en Jupyter o VS Code.
- Ejecutar celdas.

