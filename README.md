# LuloBank-DataEngineer-Test
Este proyecto tiene como objetivo realizar un análisis de las series emitidas en enero de 2024 obtenidas desde el API de TV Maze. A continuación, se detallan las actividades realizadas y cómo reproducir este proyecto.

🚀 Estructura del Proyecto

- 📂 json/           # Archivos JSON crudos obtenidos del API
- 📂 profiling/      # Reportes de profiling generados (HTML, PDF)
- 📂 data/           # Archivos Parquet generados
- 📂 db/             # Base de datos SQLite generada
- 📂 model/          # Imagen del modelo de datos
- 📂 src/            # Script .ipynb utilizado en el proyecto
- README.md          # Instrucciones de uso

📦 Instalación

Clona el repositorio:

   git clone https://github.com/kevinbecxrra/LuloBank-DataEngineer-Test

🔨 Uso

Ejecutar el notebook tvmaze_project.ipynb secuencialmente.

📈 Resultados

* averageRuntime: Runtime promedio calculado para todas las series del mes de enero de 2024.
* Conteo por Género: Archivo data/genre_counts.parquet contiene el conteo de shows por género.
* Dominios únicos de sitios oficiales: Listados en consola.

📚 Notas

Los archivos parquet generados utilizan compresión snappy para optimizar espacio y rendimiento.
La base de datos SQLite se encuentra en db/tvmaze_data.db.
