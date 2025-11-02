# 🧱 Módulo 4 — Programación Orientada a Objetos (POO)

En este módulo aprenderás a **modelar el mundo real con clases y objetos**.
La Programación Orientada a Objetos (POO) permite organizar el código en entidades lógicas con **atributos (datos)** y **métodos (comportamientos)**, favoreciendo la reutilización, la modularidad y la escalabilidad del software.

---

## 🎯 Objetivos de aprendizaje

Al finalizar este módulo, el alumno será capaz de:

* Crear clases con atributos y métodos, comprendiendo el uso de `self`.
* Diferenciar entre atributos **de instancia** y **de clase**.
* Aplicar los principios de **herencia**, **abstracción**, **polimorfismo**, **agregación** y **composición**.
* Diseñar jerarquías de clases reutilizables y extensibles.
* Comprender el uso de `super()` y el **orden de resolución de métodos (MRO)**.
* Implementar proyectos reales usando relaciones entre objetos.

---

## 📘 Estructura de notebooks

|    Nº   | Notebook                              | Contenido principal                                                                                            |
| :-----: | :------------------------------------ | :------------------------------------------------------------------------------------------------------------- |
| **4.1** | `41_clases_y_metodos.ipynb`           | Introducción a clases, atributos, métodos, constructores y tipos de métodos (`@classmethod`, `@staticmethod`). |
| **4.2** | `42_herencia_y_constructores.ipynb`   | Herencia simple y múltiple, uso de `super()`, sobrescritura de métodos y orden MRO.                            |
| **4.3** | `43_abstraccion_y_polimorfismo.ipynb` | Clases abstractas (`abc`), métodos abstractos y polimorfismo dinámico.                                         |
| **4.4** | `44_colecciones_de_objetos.ipynb`     | Relaciones entre clases: asociación, agregación y composición. Colecciones y filtrado de objetos.              |
| **4.5** | `45_lab_facturacion.ipynb`            | Laboratorio integrador: sistema de facturación orientado a objetos con herencia, polimorfismo y composición.   |

---

## 🧩 Metodología didáctica

Cada notebook incluye:

1. **Introducción teórica breve** en celdas Markdown.
2. **Ejercicios guiados** (sin resolver) con indicaciones paso a paso.
3. **Soluciones explicadas** en celdas separadas.
4. **Mini retos y extensiones** para los alumnos más avanzados.
5. **Casos de uso reales**, conectando la teoría con ejemplos del mundo profesional (empleados, facturas, pedidos, figuras, etc.).

💡 Todos los notebooks son ejecutables en **GitHub Codespaces** o **JupyterLab** sin configuración adicional.

---

## 🔧 Requisitos técnicos

* Python ≥ 3.10
* Librería estándar (`abc`, `json`, `time`)
* Editor compatible con Jupyter Notebooks (VS Code, JupyterLab o equivalente)

Para abrir el módulo desde Codespaces:

```bash
cd notebooks/modulo4_poo
code .
```

---

## 🧠 Evaluación sugerida

| Tipo de actividad            | Descripción                                                            | Peso |
| :--------------------------- | :--------------------------------------------------------------------- | :--: |
| Cuestionario teórico         | Principios de POO, herencia, polimorfismo y abstracción                | 25 % |
| Ejercicios guiados (4.1–4.4) | Desarrollo de clases y jerarquías con distintos tipos de relación      | 40 % |
| Laboratorio 4.5              | Proyecto de facturación orientado a objetos con herencia y composición | 35 % |

---

## 📚 Recursos y referencias

* [Documentación oficial de Python — Classes](https://docs.python.org/3/tutorial/classes.html)
* [PEP 3119 — Introducción de clases abstractas (ABC)](https://peps.python.org/pep-3119/)
* [Real Python — Object-Oriented Programming in Python](https://realpython.com/python3-object-oriented-programming/)
* [Refactoring.Guru — Conceptos de POO y patrones de diseño](https://refactoring.guru/es/design-patterns/python)

---

## 💬 Conclusión

La POO es uno de los pilares del desarrollo en Python.
Permite estructurar aplicaciones complejas mediante clases que **colaboran entre sí** y que pueden **evolucionar sin reescribir código**.
El dominio de estos conceptos es esencial para abordar módulos posteriores del curso como **Programación Funcional**, **Persistencia en BBDD** y **Machine Learning**.