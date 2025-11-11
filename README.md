# Actividad: Semana 4 — Análisis de datos

Este repositorio contiene los datos y el análisis de la actividad de la semana 4 del curso de Ciencia de Datos. El objetivo es procesar y explorar los conjuntos de datos proporcionados, generar resúmenes y visualizaciones relevantes, y dejar un notebook reproducible con los pasos realizados.

## Contenido del repositorio

- `actividad_semana4.csv` — Dataset principal entregado para la actividad.
- `inventario_procesado.csv` — Inventario ya procesado disponible para análisis secundarios.
- `resumen_ventas.csv` — Resumen de ventas generado o usado en el análisis.
- `analisis.ipynb` — Notebook Jupyter con el análisis paso a paso, visualizaciones y conclusiones.
- `info.json` — Metadatos o información auxiliar sobre los datos (formatos, descripciones, etc.).
- `README.md` — Este archivo con instrucciones y detalles para reproducir el trabajo.

## Objetivos

- Cargar y limpiar los datos entregados.
- Explorar las variables principales y generar estadísticas descriptivas.
- Crear visualizaciones que apoyen el análisis (series temporales, distribuciones, comparativos).
- Guardar resultados procesados en archivos CSV (`inventario_procesado.csv`, `resumen_ventas.csv`).

## Requisitos

- Python 3.8+ (recomendado 3.10 o superior)
- Paquetes principales: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter` (o `notebook`).

Si prefieres usar un entorno virtual, crea y activa uno antes de instalar dependencias.

## Instalación rápida (Windows — PowerShell)

Coloca estas líneas en PowerShell (cada línea es un comando independiente):

```powershell
python -m pip install --upgrade pip
pip install pandas numpy matplotlib seaborn jupyter
```

Nota: si usas `conda`, puedes crear un entorno y luego instalar paquetes con `conda install`/`pip` según prefieras.

## Cómo reproducir el análisis

1. Abre PowerShell en la carpeta del proyecto `c:\Users\<tu-usuario>\Ciencia de datos\fdoc_cd_act4`.
2. Asegúrate de tener las dependencias instaladas (ver sección anterior).
3. Inicia Jupyter Notebook y abre `analisis.ipynb`:

```powershell
jupyter notebook "analisis.ipynb"
```

4. Ejecuta las celdas del notebook en orden. El notebook contiene:
	- Carga de los CSVs (`actividad_semana4.csv`, `info.json`, etc.).
	- Limpieza básica (tratamiento de nulos, tipos de datos, normalización básica).
	- Análisis exploratorio (estadísticas, agrupaciones, series temporales si aplica).
	- Visualizaciones con `matplotlib`/`seaborn`.
	- Exportación de resultados a `inventario_procesado.csv` y `resumen_ventas.csv`.

## Estructura esperada de datos (breve)

- `actividad_semana4.csv`: columnas típicas pueden incluir identificador, fecha, categoría, cantidad, precio, etc.
- `info.json`: diccionario con descripciones de campos y formatos de fecha.

Si los nombres/columnas difieren, consulta las primeras celdas del notebook donde se inspecciona `head()` y `info()`.

## Buenas prácticas y notas

- Guarda siempre una copia del dataset original antes de procesarlo.
- Documenta cualquier suposición o transformación importante dentro del notebook (celdas markdown).
- Si los datos son sensibles, evita subir el repositorio a repositorios públicos.

## Posibles próximas mejoras

- Añadir un `requirements.txt` para fijar versiones.
- Incluir scripts de preprocesado independientes (por ejemplo `scripts/limpieza.py`).
- Generar pruebas unitarias mínimas para las funciones de limpieza si se extraen a módulos Python.

## Autor

MeliSando — Actividad de la semana 4 (Ciencia de Datos).

---

Si quieres, puedo generar un `requirements.txt` con versiones recomendadas o extraer parte del notebook a un script reutilizable. ¿Quieres que haga eso ahora?