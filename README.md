# Sistema-academico-java
"Sistema de gestión académica con Java y MySQL. Uso de Swing"
# Sistema de Gestión Académica

## Información del Equipo
- **Integrantes:** Felipe Quiroga, Simon Stuardo, Jorge Cañas, Alan Droguett.
- **Seccion:** 013V
- **Fecha:** 19-11-2025

## Descripción del Proyecto
Sistema de gestión académica desarrollado en Java SE con MySQL que permite administrar información de alumnos, profesores y asignaturas. Implementa operaciones CRUD completas sobre la base de datos mediante interfaz gráfica Swing.

## Funcionalidades
- ✅ Buscar alumno por RUT
- ✅ Agregar nuevo alumno
- ✅ Actualizar información de alumno
- ✅ Eliminar alumno
- ✅ Listar todos los alumnos
- ✅ Listar profesores y asignaturas

## Tecnologías Utilizadas
- Java SE
- MySQL 8.0
- JDBC
- Swing (GUI)
- NetBeans IDE

## Estructura de la Base de Datos
El sistema utiliza 3 tablas relacionadas:
- **profesores** (id_profesor, rut, nombre, especialidad)
- **asignaturas** (id_asignatura, nombre, codigo, id_profesor)
- **alumnos** (id_alumno, rut, nombre, email, id_asignatura, nota)

Ver diagrama completo en: [modelo_relacional.png](modelo_relacional.png)

## Instrucciones de Instalación

### Requisitos Previos
- Java JDK 8 o superior
- MySQL 8.0 o superior
- MySQL Workbench (recomendado)

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
