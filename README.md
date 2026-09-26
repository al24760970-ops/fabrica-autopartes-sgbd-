# Sistema de Control de Planta Industrial y Flujo de Procesos (Dos Naves)

## Descripción
Este proyecto consiste en la modelación y estructuración de una base de datos relacional para gestionar la trazabilidad de insumos, preformas y productos terminados en una planta industrial de autopartes. La fábrica cuenta con dos naves interconectadas operativamente:
* **Nave 1:** Alberga los procesos de mecanizado/herramental (**CNC**) y moldeo rotacional (**Rotoline**).
* **Nave 2:** Concentra los procesos de **Mezclado**, **Extrusión 1** (preforma Bamburi), **Extrusión 2** (pellet y polvo de plástico), **Inyección** y **Compresión** (filtros y tapetes).

El objetivo principal es asegurar la integridad referencial y el control lógico del flujo de materia prima entre las distintas áreas de la planta (como el envío de polvo desde Extrusión 2 hacia Rotoline).

## Datos del Estudiante
* **Nombre:** Héctor Soto Radilla
* **Programa Educativo:** Ingeniería en Sistemas Computacionales
* **Institución:** Tecnológico Nacional de México Campus Ensenada

## Estructura del Repositorio
El repositorio está organizado con la siguiente estructura de carpetas y archivos:

* `README.md`: Documentación principal del proyecto, descripción operativa y guía de ejecución.
* `database/`:
  * `schema.sql`: Script DDL para la creación de la base de datos, tablas, llaves primarias, llaves foráneas y restricciones (`CHECK`, `UNIQUE`, `DEFAULT`).
  * `data.sql`: Script DML con la inserción de datos iniciales del catálogo de naves, áreas operativas y productos/materia prima.

