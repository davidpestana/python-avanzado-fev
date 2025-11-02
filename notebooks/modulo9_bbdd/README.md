# 🗄️ Módulo 9 — Acceso a Bases de Datos Relacionales

## 🧭 Objetivos del módulo

En este módulo aprenderás a **conectar, consultar y manipular bases de datos relacionales** desde Python utilizando **SQLite** como motor principal.

SQLite es una base de datos **ligera, sin servidor** y perfecta para el aprendizaje o para proyectos locales.
Una vez dominado su uso, podrás aplicar los mismos conceptos con **PostgreSQL, MySQL o SQL Server**, cambiando únicamente el controlador.

Aprenderás a:

* Crear y gestionar bases de datos con SQLite desde Python.
* Ejecutar sentencias SQL (CREATE, SELECT, UPDATE, DELETE).
* Integrar consultas SQL con **Pandas** para análisis.
* Modelar relaciones entre tablas y usar **JOINs**.
* Construir un mini sistema CRUD (tickets de soporte) desde cero.

---

## 📚 Contenido de los notebooks

| Nº      | Notebook                     | Descripción breve                                                                |
| ------- | ---------------------------- | -------------------------------------------------------------------------------- |
| **9.1** | `91_sqlite_basico.ipynb`     | Introducción a SQLite: conexión, creación de tablas e inserción de datos.        |
| **9.2** | `92_crud_desde_python.ipynb` | Operaciones CRUD completas (Create, Read, Update, Delete) desde Python y Pandas. |
| **9.3** | `93_lab_tickets.ipynb`       | Laboratorio final: sistema de gestión de tickets con varias tablas y relaciones. |

---

## 🧩 Actividades prácticas

Durante este módulo los alumnos:

* Construirán y consultarán una base de datos SQLite (`ventas.db` y `tickets.db`).
* Ejecutarán operaciones CRUD paso a paso desde Python.
* Practicarán consultas SQL avanzadas (`JOIN`, `GROUP BY`, `WHERE`).
* Desarrollarán un mini **sistema de tickets** con usuarios, categorías y estados.
* Aprenderán a integrar SQL con **Pandas DataFrames** para análisis tabular.

---

## 💡 Recomendaciones didácticas

* Asegúrate de ejecutar primero el **notebook 9.1** para crear la base de datos inicial.
* Refuerza los conceptos de **modelado relacional** antes de pasar al laboratorio.
* Propón pequeñas modificaciones (añadir columna “prioridad” o “fecha cierre”) como mini-retos.
* Motiva a los alumnos a exportar sus resultados o combinar SQLite con **Dashboards** o **APIs**.

---

## 🧠 Resultados de aprendizaje

Al finalizar este módulo, los alumnos serán capaces de:

* Crear y consultar bases de datos relacionales desde Python.
* Ejecutar operaciones CRUD seguras y eficientes.
* Comprender el uso de claves primarias y foráneas.
* Desarrollar un mini sistema de gestión basado en SQL y Pandas.
* Estar preparados para conectar con **bases de datos externas** (PostgreSQL, MySQL, etc.).
