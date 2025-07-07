# Búsquedas en Python - Tarea SI516-A

Este repositorio contiene implementaciones de algoritmos de búsqueda desarrollados en Python como parte del trabajo práctico de la materia **Sistemas Inteligentes e Innovación (SI516-A)**.

Los algoritmos utilizados fueron mayormente extraídos directamente del [repositorio oficial del libro, escrito en Python](https://github.com/aimacode/aima-python/)

La tarea a resolver fue dada por lo visto en [UPSAVirtual](https://virtual.upsa.edu.bo)

**Estudiante:** Antonio Miguel Natusch Zarco  
**Fecha de entrega:** 7 de julio de 2025  
**Temas asignados:**  
- Búsqueda voraz (Greedy Best-First Search)  
- Búsqueda A\* (A\* Search)  
- Búsqueda A\* con pesos (Weighted A\*)  
- Haz local (Local Beam Search)

---

## 📁 Estructura del repositorio

```
aima-python-lite/
│
├── search.ipynb           # Notebook principal con explicaciones, ejemplos y visualizaciones
├── search.py              # Implementación de clases base (Problem, Node) y algoritmos de búsqueda
├── utils.py               # Funciones auxiliares utilizadas por search.py (colas, heurísticas, etc.)
├── notebook.py            # Utilidades para visualización interactiva (pseudocódigo, gráficos)
├── requirements.txt       # Lista de dependencias necesarias
├── .gitignore             # Exclusión de archivos innecesarios en control de versiones
├── docs/                  # Documentos de apoyo para la presentación
│   ├── Resúmenes de búsquedas - Antonio Natusch.pdf
│   └── Presentación Búsquedas.pdf
├── homework.png           # Captura de pantalla del apartado de la tarea según la plataforma
└── README.md              # Este archivo
```

---

## 🛠️ Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/tuusuario/aima-python-lite.git
cd aima-python-lite
```

2. Instalar las dependencias necesarias:

```bash
pip install -r requirements.txt
```

---

## 📓 Uso del Notebook

Este proyecto utiliza un único notebook llamado `search.ipynb`, que contiene todo el desarrollo para los algoritmos asignados.

### Instalación de Jupyter Notebook:

```bash
pip install notebook
```

### Ejecutar en una terminal:

```bash
jupyter notebook
```

Abrí el archivo `search.ipynb` y ejecutá cada celda paso a paso para ver el comportamiento de los algoritmos de búsqueda.

---

## 🗂️ Documentación adicional

El directorio `docs/` contiene el material de apoyo que acompaña la exposición de la tarea:
- Un resumen con los conceptos clave y algoritmos abordados (`Google Docs`, exportado a PDF)
- Una presentación visual desarrollada en `Canva` (exportada a PDF)

---

## 📚 Referencias

- Russell, S. J., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach*. Pearson.
- Sharma, S. (2020). [Local Beam Search Algorithm in AI](https://youtu.be/Ad29SjJ1GwA)

---

Este trabajo incluye la implementación, explicación y ejemplos de los algoritmos asignados, acompañado de material de presentación como parte del avance de la evaluación parcial.
