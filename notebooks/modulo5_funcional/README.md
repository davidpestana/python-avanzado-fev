# 🧠 Módulo 5 — Programación Funcional en Python

La **programación funcional** es un paradigma que trata las operaciones como transformaciones sobre datos, sin modificar su estado ni usar variables globales.
Python no es puramente funcional, pero ofrece potentes herramientas que permiten aplicar este estilo de manera expresiva y eficiente.

---

## 🎯 Objetivos de aprendizaje

Al finalizar este módulo, el alumno será capaz de:

* Comprender los principios de la **programación funcional** y sus ventajas.
* Usar **funciones lambda** para operaciones rápidas y expresivas.
* Crear y manipular colecciones mediante **comprensiones**.
* Aplicar funciones integradas (`zip`, `any`, `all`) en flujos declarativos.
* Transformar, filtrar y combinar datos con `map()`, `filter()` y `reduce()`.
* Encadenar funciones funcionales para crear pipelines de procesamiento.
* Resolver problemas complejos sin bucles ni mutaciones de estado.

---

## 📘 Estructura de notebooks

|    Nº   | Notebook                         | Contenido principal                                                                      |
| :-----: | :------------------------------- | :--------------------------------------------------------------------------------------- |
| **5.1** | `51_lambda_comprehensions.ipynb` | Funciones lambda, comprensiones de listas, sets y diccionarios.                          |
| **5.2** | `52_zip_any_all.ipynb`           | Uso de funciones integradas para combinar, verificar y comparar colecciones.             |
| **5.3** | `53_map_filter_reduce.ipynb`     | Transformación, filtrado y reducción de colecciones mediante funciones funcionales.      |
| **5.4** | `54_lab_transformaciones.ipynb`  | Laboratorio práctico: análisis y ranking de ventas usando flujos funcionales compuestos. |

---

## 🧩 Metodología didáctica

Cada notebook combina:

1. **Explicaciones teóricas breves** en celdas Markdown.
2. **Ejercicios guiados** con indicaciones paso a paso.
3. **Soluciones explicadas** en celdas separadas.
4. **Casos de uso prácticos** con listas, tuplas, diccionarios y datos reales.
5. Un **laboratorio integrador** que aplica todos los conceptos en conjunto.

💡 Todos los notebooks son completamente ejecutables en **GitHub Codespaces** o **JupyterLab**, sin configuración adicional.

---

## 🔧 Requisitos técnicos

* Python ≥ 3.10
* Librerías estándar: `functools`, `itertools`
* Editor compatible con Jupyter Notebooks (VS Code o JupyterLab)

Para abrir el módulo desde Codespaces:

```bash
cd notebooks/modulo5_funcional
code .
```

---

## 🧠 Evaluación sugerida

| Tipo de actividad            | Descripción                                                         | Peso |
| :--------------------------- | :------------------------------------------------------------------ | :--: |
| Cuestionario teórico         | Conceptos de programación funcional, lambdas y funciones integradas | 25 % |
| Ejercicios guiados (5.1–5.3) | Aplicación práctica de transformaciones funcionales                 | 40 % |
| Laboratorio 5.4              | Proyecto de análisis funcional con map/filter/reduce/zip            | 35 % |

---

## 📚 Recursos y referencias

* [Documentación oficial de Python — Functional Programming HOWTO](https://docs.python.org/3/howto/functional.html)
* [PEP 309 — Partial function application](https://peps.python.org/pep-0309/)
* [Real Python — Functional Programming in Python](https://realpython.com/python-functional-programming/)
* [Python Docs — functools.reduce](https://docs.python.org/3/library/functools.html#functools.reduce)

---

## 💬 Conclusión

La programación funcional aporta **claridad, expresividad y menor acoplamiento**.
Permite trabajar con datos de forma más segura y escalable, lo que la hace ideal para **procesos ETL, análisis de datos y machine learning**.

Este módulo prepara al alumno para trabajar de forma fluida con colecciones y para abordar los siguientes temas del curso:
📁 **Entrada/Salida de datos y serialización (Módulo 6)** y 📈 **Procesamiento estructurado con Numpy y Pandas (Módulo 7)**.

