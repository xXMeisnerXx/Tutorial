# Tutorial de Python para principiantes · Parte 1

**Variables, tipos de datos y estructuras**

Notebook de estudio basado en las sesiones 3 y 4 del curso. Cada función tiene una explicación corta en
español y un solo ejemplo listo para ejecutar.

**Autor:** Felipe Giraldo Zapata

---

## Contenido

| # | Sección | Qué incluye |
|---|---|---|
| 1 | Variables y tipos de datos | `int`, `float`, `str`, `bool`, `print()`, f-strings, `type()`, `del` |
| 2 | Operaciones | Aritméticas, comparaciones, `and` / `or` / `not`, `isinstance()`, concatenar textos |
| 3 | Conversión de tipos | `str()`, `int()`, `float()` |
| 4 | Métodos de texto | `.upper()`, `.lower()`, `.title()`, `.capitalize()`, `.startswith()`, `.endswith()`, `.isalpha()`, `.isnumeric()`, `.replace()`, `.split()`, `.strip()` |
| 5 | Tuplas | Crear, `.count()`, desempaquetar, `len()` |
| 6 | Listas | `.append()`, `.remove()`, `+`, `.extend()`, `.insert()`, `.pop()`, `.sort()`, `=` frente a `.copy()` |
| 7 | Conjuntos | `set()`, `.add()`, `.intersection()`, `.union()`, `.difference()` |
| 8 | Diccionarios | `{}`, `dict()`, `.keys()`, `.values()`, `.items()`, `.get()`, `.update()`, `.pop()` |
| 9 | Indexación y slicing | `[i]`, `[-i]`, `[clave]`, `[inicio:fin]`, `[::paso]`, `[::-1]`, modificar posiciones y rangos |

## Archivos

| Archivo | Descripción |
|---|---|
| [`Tutorial_Python.ipynb`](Tutorial_Python.ipynb) | El tutorial, con las salidas de cada ejemplo |
| `README.md` | Este archivo |

## Requisitos

- Python 3.8 o superior (probado con Python 3.13).
- [VS Code](https://code.visualstudio.com/) con la extensión **Jupyter**, o cualquier entorno que abra
  notebooks (`.ipynb`).
- El paquete `ipykernel`, que permite ejecutar las celdas.

El tutorial solo usa Python estándar: no necesita librerías externas.

## Cómo ejecutarlo

1. Clona el repositorio y entra en la carpeta:

    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    cd tu-repositorio
    ```

2. Crea un entorno virtual e instala `ipykernel`:

    ```bash
    python -m venv .venv
    .venv\Scripts\activate        # Windows
    source .venv/bin/activate     # macOS / Linux
    pip install ipykernel
    ```

3. Abre `Tutorial_Python.ipynb` en VS Code y elige el entorno `.venv` como kernel, arriba a la
   derecha.

4. Ejecuta las celdas **en orden** con `Shift + Enter`, o todas a la vez con **Run All**.

## Cómo está organizado

- Cada función tiene un título, una explicación de una o dos líneas y una celda de código.
- Las líneas que empiezan con `#` son comentarios: Python no las ejecuta.
- Las líneas que producirían un error, por ejemplo un `IndexError`, están comentadas con la nota
  *"Quita el # para ver el error"*. Así **Run All** no se detiene a mitad del notebook.
- Varias celdas usan variables creadas en celdas anteriores. Si saltas una, puedes recibir un
  `NameError`.

## Siguiente parte

**Parte 2: control de flujo, funciones y módulos.** Cubre `if` / `elif` / `else`, ciclos `for`,
`range()`, `enumerate()`, `zip()`, comprensiones, funciones (type hints, docstrings y alcance) y módulos.
