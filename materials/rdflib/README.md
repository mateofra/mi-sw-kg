# Prácticas de RDFLib (Web Semántica)

Este repositorio contiene material para aprender a usar **RDFLib** en Python.

- **Ejercicios 1–4**: están **resueltos** → ejecuta, lee y entiende (puedes hacer pequeñas modificaciones para comprobar que lo has entendido).
- **Ejercicios 5–6**: son **para hacer** → completa el código donde se indique.

---

## Requisitos

- Python **3.10+** (recomendado)
- Git
- (Opcional) Jupyter Notebook y/o VS Code / PyCharm

---

## 1) Crear un entorno virtual 

Lo puedes hacer también desde VSCode o PyCharm
Ejecuta esto desde la **raíz del repositorio**:

### macOS / Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```
### Windows (PowerShell)
```bash
py -m venv .venv
.\.venv\Scripts\Activate.ps1
```

## 2) Instalar dependencias

Con el entorno activado:
```bash
pip install -r requirements.txt
```

## 3) Qué se espera de ti
- Ejercicios 1–4 (resueltos):
  - Ejecuta el material.
  - Lee el código con calma.
  - Comprueba qué triples se añaden, cómo se serializa el grafo (p. ej. Turtle) y cómo se consulta (si aplica).
  - Haz cambios pequeños (URIs, literales, namespaces, consultas) para verificar que lo entiendes.
- Ejercicios 5–6 (para hacer):
  - Completa las partes marcadas como TODO o indicadas en el enunciado.
  - Tu objetivo es que el resultado coincida con lo que se pide (salida esperada / consultas / serialización / validaciones).