# 📚 Sistema de Biblioteca

Sistema de gestión de biblioteca desarrollado en **Java** con **SQLite**, orientado a la gestión de libros, socios y préstamos mediante una aplicación de consola.

El proyecto forma parte de mi formación en **Desarrollo de Aplicaciones Web (DAW)** y trabaja conceptos de programación orientada a objetos, acceso a bases de datos, validación de datos y consultas SQL.

## 🛠️ Tecnologías

* ☕ Java
* 🗄️ SQLite
* 🔎 SQL
* 🧩 Programación Orientada a Objetos
* 🔧 Git y GitHub

## 📋 Funcionalidades

### 📖 Gestión de libros

Permite:

* Insertar libros con ISBN, título, escritor, año y puntuación.
* Eliminar libros mediante su código.
* Comprobar si un libro existe antes de eliminarlo.
* Evitar la eliminación de libros relacionados con préstamos.
* Consultar todos los libros.
* Consultar libros por escritor.
* Ordenar libros por puntuación descendente.
* Consultar libros que nunca han sido prestados.
* Consultar libros devueltos en una fecha determinada.

### 👥 Gestión de socios

Permite:

* Insertar socios con DNI, nombre, domicilio, teléfono y correo.
* Eliminar socios mediante su código.
* Comprobar si el socio existe antes de eliminarlo.
* Evitar la eliminación de socios relacionados con préstamos.
* Consultar todos los socios.
* Consultar socios por localidad.
* Ordenar socios por nombre ascendente.
* Consultar socios sin préstamos.
* Consultar socios con préstamos en una fecha determinada.

### 🔄 Gestión de préstamos

Permite:

* Crear préstamos.
* Comprobar la disponibilidad de un libro.
* Comprobar que el socio no tenga otro préstamo pendiente.
* Actualizar la fecha de devolución.
* Eliminar préstamos mediante datos identificativos.
* Consultar todos los préstamos.
* Consultar préstamos no devueltos.
* Consultar información combinada de socios, libros y fechas.

### 📊 Consultas avanzadas

El proyecto incluye consultas SQL para obtener:

* Libro o libros prestados menos veces.
* Socio o socios con más préstamos.
* Libros prestados menos veces que la media.
* Socios con más préstamos que la media.
* Libros ordenados por número de préstamos.
* Socios ordenados por número de préstamos.

Estas consultas trabajan con funciones de agregación, medias, ordenación y relaciones entre las diferentes tablas.

## 🗃️ Base de datos

El proyecto utiliza **SQLite** para almacenar la información.

La base de datos `biblioteca.db` contiene tres entidades principales:

* `libro`
* `socio`
* `prestamo`

El archivo `biblioteca_sql.md` contiene la creación de la base de datos y de sus tablas.

## 🧩 Clases auxiliares

### `Teclado.java`

Clase reutilizable para gestionar la entrada de datos desde consola.

### `FuncionesRegex.java`

Clase utilizada para validar diferentes tipos de datos mediante expresiones regulares y lógica adicional.

### `biblioteca_sql.md`

Documento con la estructura SQL necesaria para crear la base de datos y sus tablas.

## 📁 Estructura general

```text
Sistema-Biblioteca/
├── Sistema-Biblioteca/
│   ├── Actividad_2x01
│   ├── Actividad_2x02
│   ├── Actividad_2x03
│   ├── Actividad_2x04
│   ├── Teclado.java
│   └── FuncionesRegex.java
├── biblioteca_sql.md
└── README.md
```

La estructura exacta de paquetes y clases puede variar según la organización utilizada durante el desarrollo.

## 🎯 Objetivos del proyecto

Este proyecto trabaja principalmente:

* Programación orientada a objetos con Java.
* Gestión de datos mediante SQLite.
* Consultas SQL.
* Relaciones entre tablas.
* Validación de datos.
* Operaciones CRUD.
* Consultas con condiciones y ordenación.
* Consultas de agregación y estadísticas.
* Organización del código mediante clases auxiliares.

## 🚀 Ejecución

1. Clona el repositorio:

```bash
git clone https://github.com/danpanzgz/Sistema-Biblioteca.git
```

2. Abre el proyecto en tu IDE.

3. Comprueba que tienes un JDK compatible instalado.

4. Crea la base de datos SQLite siguiendo las instrucciones de:

```text
biblioteca_sql.md
```

5. Ejecuta las clases correspondientes a cada actividad.

## 📚 Actividades

### Actividad 2x01

Gestión y consultas de libros.

### Actividad 2x02

Gestión y consultas de socios.

### Actividad 2x03

Gestión de préstamos y consultas relacionadas.

### Actividad 2x04

Consultas avanzadas y estadísticas sobre libros y socios.

## 👨‍💻 Autor

**Dan Bolocan**

Estudiante de Desarrollo de Aplicaciones Web (DAW).

GitHub:
https://github.com/danpanzgz

Portfolio:
https://cv.danbolocan13.workers.dev/

## 📄 Licencia

Proyecto académico desarrollado con fines educativos.
