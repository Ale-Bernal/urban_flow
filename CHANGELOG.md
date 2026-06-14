
---
## [Día 1] - 2026-04-26
**Cambios realizados:**
- Estructura de directorios base.
- README.md inicial.


---
## [Día 2] - 2026-04-26
**Cambios realizados:**
- Descarga del dataset raw original y almacenamiento.- Muestra de las 5 primeras filas del dataset.- Análisis de tipos de datos.- Conteo de valores nulos.

---
## [Día 3] - 2026-04-26
**Cambios realizados:**
- Normalización de fechas, horas, ubicaciones y patentes.
- Eliminación de registros con nulos en columnas relevantes.
- Detección y tratamiento de outliers.
- Cálculo de exceso de velocidad y filtrado de infracciones.


---
## [Día 4] - 2026-04-26
**Cambios realizados:**
- Implementación de clase FineAnalyzer para análisis de datos.
- Generación de rankings de patentes, horarios y métricas de velocidad.


---
## [Día 5] - 2026-04-26
**Cambios realizados:**
- Generación de gráfico de ranking de las 10 patentes más reincidentes.
- Generación de gráfico de porcentaje de infracciones por hora.
- Generación de gráfico de cantidad de infracciones por mes.
- Generación de gráfico de excesos de velocidad agrupados por la hora 00:00.
- Generación de gráfico de excesos de velocidad agrupados por la fecha 1932-01-01.


---
## [Día 6] - 2026-04-26
**Cambios realizados:**
- Cálculo y análisis del porcentaje de infracciones ocurridas en la fecha por defecto (1932-01-01), que representa el 77.29% del total.
- Cálculo y análisis del porcentaje de infracciones ocurridas en la hora por defecto (00:00), que representa el 19.79% del total.


---
## [Día 7] - 2026-04-26
**Cambios realizados:**
- Se realizón una conclusión acerca de los datos que contiene el dataset..


---
## [Día 1] - 2026-05-25
### Inicialización del Sprint 2

- Clonado del repositorio del Sprint 1.
- Creación de la rama Sprint_2 a partir de Sprint_1.
- Descarga y descompresión del dataset de imágenes en data/raw/imgs.


---
## [Día 2] - 2026-05-25
### Exploración del dataset de imágenes

- Listado de imágenes con su tamaño en kb.
- Clasificación de imágenes en plates y completes por área.
- Construcción del diccionario group_images y guardado en data/interim/group_images.json.
- Función reutilizable mostrar_muestra_imagenes.


---
## [Día 3] - 2026-05-25
### Pipeline de procesamiento de imágenes

- Conversión a escala de grises de las imágenes originales.
- Suavizado Gaussiano sobre las imágenes en grises.
- Detección de bordes sobre las imágenes suavizadas.


---
## [Día 4] - 2026-05-25
### Extracción de patentes y match con dataset

- Aplicación de extraer_patente sobre todas las imágenes.
- Match izquierda a derecha contra speeding_fines.csv con umbral del 80%.
- Generación de data/processed/speeding_fines_image.csv con las columnas imagen, patente_imagen y ratio.


---
## [Día 5] - 2026-05-25
### Métricas finales del Sprint 2

- Métricas de multas con y sin imagen, imágenes sin match y multas pendientes de pago.


---
## [Día 6] - 2026-05-25
### Conclusión del Sprint 2

- Conclusión final del Sprint 2 escrita en data/Readme.md.

[Día 1] - 2026-06-14
Inicialización del Sprint 3

* Clonado del repositorio del Sprint 2.
* Creación de la rama Sprint_3 a partir de Sprint_2.
* Configuración del README.md con objetivo y contexto del sprint.

