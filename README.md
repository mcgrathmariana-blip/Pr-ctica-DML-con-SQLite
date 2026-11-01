# Práctica DML con SQLite

## Descripción
Este proyecto tiene como objetivo practicar las operaciones DML (Data Manipulation Language) utilizando SQLite y Python en Google Colab.

## Base de datos
Se creó la base de datos `practica_dml.db`, que contiene la tabla `vendedores` con los siguientes campos:

- `id`: identificador del vendedor (clave primaria).
- `nombre`: nombre del vendedor.
- `ventas_totales`: total de ventas.
- `zona`: zona de trabajo.
- `fecha_ingreso`: fecha de ingreso.

## Operaciones realizadas

1. **CREATE:** creación de la tabla `vendedores`.
2. **INSERT:** carga de registros iniciales y agregado de nuevos vendedores.
3. **INSERT masivo:** inserción de tres vendedores en una sola operación.
4. **SELECT:** consulta de vendedores pertenecientes a la zona Norte.
5. **UPDATE:** actualización de las ventas del vendedor con ID 2, sumando 500.
6. **UPDATE con condición:** modificación de la zona a Internacional para vendedores con más de 10.000 en ventas.
7. **DELETE:** eliminación del vendedor de prueba con ID 10.
8. **SELECT final:** verificación de los registros restantes.

## Archivos del proyecto

- `Practica_DML_SQLite.ipynb`: notebook con el desarrollo y ejecución de los ejercicios.
- `practica_dml.db`: archivo de la base de datos SQLite.
- `README.md`: documentación del proyecto.

## Herramientas utilizadas
- Python
- SQLite
- Google Colab
