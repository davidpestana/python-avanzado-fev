# 💾 Módulo 6 — Entrada/Salida y Serialización de Datos

En este módulo aprenderás cómo **Python interactúa con el sistema de archivos**, gestiona la **lectura y escritura de datos** y cómo **serializa información compleja** (listas, diccionarios, objetos, configuraciones, etc.) para guardarla o compartirla.

---

## 🎯 Objetivos de aprendizaje

Al finalizar este módulo, el alumno será capaz de:

* Trabajar con **archivos y directorios** usando `os` y `pathlib`.
* Leer y escribir archivos de texto de forma segura con el bloque `with open()`.
* Controlar el cursor de lectura (`seek()` y `tell()`).
* Persistir estructuras complejas con **serialización binaria (`pickle`, `shelve`)**.
* Usar formatos estructurados de datos como **JSON** y **XML**.
* Implementar un sistema real de **configuración persistente** con lectura y logs automáticos.

---

## 📘 Estructura de notebooks

|    Nº   | Notebook                                | Contenido principal                                              |
| :-----: | :-------------------------------------- | :--------------------------------------------------------------- |
| **6.1** | `61_gestion_archivos_directorios.ipynb` | Uso de `os` y `pathlib` para gestionar archivos y carpetas.      |
| **6.2** | `62_lectura_secuencial.ipynb`           | Lectura línea a línea, cursores y análisis básico de texto.      |
| **6.3** | `63_serializacion_binaria.ipynb`        | Serialización binaria con `pickle` y `shelve`.                   |
| **6.4** | `64_json_xml.ipynb`                     | Serialización de datos con JSON y XML.                           |
| **6.5** | `65_lab_configuracion_usuario.ipynb`    | Laboratorio final: sistema de configuración y logs persistentes. |

---

## 🧩 Metodología didáctica

Cada notebook incluye:

1. **Explicaciones teóricas cortas** y contextualizadas.
2. **Ejercicios guiados** con instrucciones paso a paso.
3. **Soluciones propuestas** en celdas separadas para comparación.
4. **Casos prácticos** que simulan usos reales (logs, inventarios, configuración).
5. **Laboratorio final integrador** que combina todos los conceptos.

💡 Los notebooks pueden ejecutarse directamente en **GitHub Codespaces** o **JupyterLab** sin configuración adicional.

---

## 🧰 Contenidos y módulos prácticos

### 🔹 Gestión del sistema de archivos

* Crear, listar y eliminar directorios (`os`, `pathlib`).
* Leer y escribir archivos (`open()` con `with`).
* Manejar errores (`FileNotFoundError`, `PermissionError`).

### 🔹 Lectura de texto y cursores

* Lectura completa (`.read()`), parcial (`.readline()`, `.readlines()`).
* Iteración eficiente línea a línea.
* Control del cursor con `.seek()` y `.tell()`.

### 🔹 Serialización y persistencia

* Serialización binaria con `pickle` (guardar estructuras Python).
* Almacenamiento de objetos en base de datos ligera con `shelve`.
* Uso de **JSON** (formato estándar web) y **XML** (estructuras jerárquicas).

### 🔹 Proyecto final del módulo

* Sistema completo de **configuración persistente del usuario**.
* Registro de logs con fecha y hora.
* Lectura, modificación y resumen de configuración en JSON.

---

## 🔧 Requisitos técnicos

* Python ≥ 3.10
* Módulos estándar: `os`, `pathlib`, `pickle`, `shelve`, `json`, `xml.etree.ElementTree`, `datetime`.
* Editor compatible con Jupyter (VS Code o JupyterLab).

Para abrir el módulo desde Codespaces:

```bash
cd notebooks/modulo6_io
code .
```

---

## 🧠 Evaluación sugerida

| Tipo de actividad            | Descripción                                               | Peso |
| :--------------------------- | :-------------------------------------------------------- | :--: |
| Cuestionario teórico         | Conceptos de E/S, `with`, `seek`, `pickle`, `json`, `xml` | 25 % |
| Ejercicios guiados (6.1–6.4) | Prácticas de lectura, escritura y serialización           | 45 % |
| Laboratorio 6.5              | Desarrollo del sistema de configuración persistente       | 30 % |

---

## 📚 Recursos recomendados

* [Documentación oficial de Python — I/O](https://docs.python.org/3/tutorial/inputoutput.html)
* [Python Docs — pathlib](https://docs.python.org/3/library/pathlib.html)
* [Python Docs — pickle](https://docs.python.org/3/library/pickle.html)
* [Python Docs — json](https://docs.python.org/3/library/json.html)
* [Python Docs — xml.etree.ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html)

---

## 💬 Conclusión

El módulo introduce una de las capacidades más poderosas de Python: **la persistencia de datos**.
Desde simples archivos de texto hasta configuraciones estructuradas, el alumno aprende a guardar, recuperar y manipular información de manera profesional.

Este conocimiento prepara el terreno para el siguiente bloque:
📊 **Módulo 7 — Procesamiento de Datos con Numpy y Pandas**, donde los datos se manipulan a gran escala.
