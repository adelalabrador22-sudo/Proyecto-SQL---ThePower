# Proyecto-SQL---ThePower
Proyecto: DataProject: Lógica. Consultas de SQL

Para este proyecto he utilizado la base de datos de pruebas clásica Sakila.
Incluye el script para crear el esquema completo (tablas para películas, actores, alquileres, clientes, etc.) basándome en el diagrama entidad-relación proporcionado.

¿Qué incluye este proyecto?
El archivo principal contiene la resolución de los ejercicios, que cubren desde lo más básico hasta conceptos más avanzados:
1. Gestión del Esquema
  Creación del esquema de la BD desde cero.
  Uso de tipos de datos, claves primarias y foráneas.
2. Consultas y Filtrado
  Búsquedas básicas (WHERE, LIKE, BETWEEN).
  Filtrado por condiciones de edad (R, PG-13), duración y disponibilidad.
  Uso de DISTINCT para obtener valores únicos.
3. Agregaciones y Funciones
  Cálculo de totales, medias, varianza y desviación estándar (ej: costes de reemplazo o duración de películas).
  Uso de GROUP BY y HAVING para agrupar resultados (ej: número de alquileres por mes o por categoría).
4. Joins y Relación de Tablas
  Conexión entre tablas (film, category, actor, rental, etc.).
  Diferencias prácticas entre INNER JOIN, LEFT JOIN, RIGHT JOIN y CROSS JOIN.
  Búsqueda de actores que no tienen películas o películas sin alquileres.
5. Subconsultas y Lógica Avanzada
  Comparaciones con subqueries (ej: películas más caras que la media, clientes que gastan más que otros).
  Creación de Vistas para guardar consultas frecuentes.
  Uso de Tablas Temporales para almacenar resultados intermedios (como el total de alquileres por cliente).

Cómo usarlo:
Si quieres ejecutar este proyecto, asegúrate de tener una instancia de SQL (MySQL o PostgreSQL) con el esquema de Sakila cargado. Luego puedes ir ejecutando los scripts en orden para ver los resultados de cada ejercicio.
# Proyecto realizado con fines educativos para consolidar conocimientos de SQL.
