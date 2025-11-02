# 🧠 Módulo 3 — Funciones Avanzadas en Python

Las **funciones** son el pilar de la modularidad y la reutilización del código en Python.
En este módulo profundizamos en la creación de funciones avanzadas, el uso de argumentos variables, el manejo del ámbito de las variables y los **decoradores**, una de las herramientas más potentes del lenguaje.

---

## 🎯 Objetivos de aprendizaje

Al finalizar el módulo, el alumno será capaz de:

* Comprender y aplicar los distintos tipos de **parámetros y argumentos** (`*args`, `**kwargs`).
* Usar correctamente el **modelo LEGB** (Local, Enclosing, Global, Built-in).
* Definir funciones anidadas y **closures** para encapsular comportamiento.
* Crear **decoradores** simples y con parámetros.
* Encadenar decoradores y combinar su comportamiento.
* Diseñar funciones reutilizables con validación, registro y control de tiempo.

---

## 📘 Estructura de notebooks

|    Nº   | Notebook                        | Contenido principal                                                                         |
| :-----: | :------------------------------ | :------------------------------------------------------------------------------------------ |
| **3.1** | `31_funciones_avanzadas.ipynb`  | Definición de funciones, retorno múltiple, *args, **kwargs y ámbito básico (LEGB).          |
| **3.2** | `32_parametros_variables.ipynb` | Uso avanzado de *args y **kwargs, `nonlocal`, funciones anidadas y primeros decoradores.    |
| **3.3** | `33_closures_decoradores.ipynb` | Cierres, creación de decoradores, decoradores con parámetros y encadenados.                 |
| **3.4** | `34_lab_funciones.ipynb`        | Laboratorio práctico integrador: sistema de validación, registro y medición de operaciones. |

---

## 🧩 Metodología didáctica

Cada notebook combina:

1. **Bloques teóricos cortos** en celdas Markdown con ejemplos claros.
2. **Ejercicios guiados** con espacio para que el alumno los resuelva.
3. **Soluciones explicadas** en celdas separadas.
4. **Ejercicios integradores** para consolidar conceptos y aplicar creatividad.

💡 Todos los notebooks están diseñados para ser ejecutados directamente en **GitHub Codespaces** o **JupyterLab**.

---

## 🔧 Requisitos técnicos

* Python ≥ 3.10
* Librerías estándar (`functools`, `time`)
* Editor compatible con Jupyter Notebooks (VS Code o JupyterLab)

Para abrir el módulo desde Codespaces:

```bash
cd notebooks/modulo3_funciones
code .
```

---

## 🧠 Evaluación sugerida

| Tipo de actividad            | Descripción                                            | Peso |
| :--------------------------- | :----------------------------------------------------- | :--: |
| Cuestionario teórico         | Preguntas sobre ámbito, *args, **kwargs y closures     | 25 % |
| Ejercicios guiados (3.1–3.3) | Desarrollo y comprensión práctica de funciones         | 35 % |
| Laboratorio 3.4              | Proyecto integrador: sistema con decoradores aplicados | 40 % |

---

## 📚 Recursos y referencias

* [Documentación oficial de Python — Defining Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
* [PEP 318 — Decorators for Functions and Methods](https://peps.python.org/pep-0318/)
* [Real Python — Python Decorators: A Complete Guide](https://realpython.com/primer-on-python-decorators/)
* [Python.org — Scopes and Namespaces](https://docs.python.org/3/tutorial/classes.html#python-scopes-and-namespaces)