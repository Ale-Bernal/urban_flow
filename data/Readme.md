
## Conclusion - Sprint 3
sssssss
En este Sprint se profesionalizo la solucion de Urban Flow migrando de un
flujo basado en archivos CSV a una arquitectura con persistencia
estructurada y versionado de datos segun su tipo. Los datos de texto se
mantienen bajo git, mientras que los binarios (imagenes) se versionan con
DVC contra un remote local, lo que mantiene el repositorio liviano y
reproducible.

La informacion procesada se modelo primero como clases de dominio y luego
se persistio en una base relacional con SQLAlchemy, lo que permitio
resolver consultas de negocio (patentes mas multadas, radares mas activos,
reincidencia por periodo y porcentaje de confirmacion visual) de forma
declarativa y eficiente.

Finalmente, la integracion de una base vectorial (ChromaDB + OpenCLIP)
habilita la busqueda de un vehiculo a partir de una imagen por similitud,
sentando las bases para busquedas avanzadas en futuras iteraciones del
sistema.
