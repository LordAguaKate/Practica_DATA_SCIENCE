# Práctica de Data Science

Repositorio con notebooks de práctica para aprender y aplicar conceptos fundamentales de Python y análisis de datos con Pandas. Incluye ejemplos de uso de bibliotecas, funciones, estructuras de datos, manejo de excepciones y un ejercicio práctico de análisis exploratorio con una base de inmuebles de CDMX.

## Contenidos
- **Copia_de_Python_para_Data_SCIENCE.ipynb**
  - Introducción a Python para ciencia de datos
  - Instalación e importación de bibliotecas
  - Funciones (built-in, definidas, lambda), comprensión de listas y diccionarios
  - Manejo de excepciones (try/except/else/finally)
  - Ejemplos con `matplotlib` y `random`

- **inmuebles_CDMX.ipynb**
  - Carga de datos con `pandas.read_csv`
  - Exploración inicial (head, tail, info, shape, sample)
  - Limpieza: tratamiento de nulos y registros inconsistentes
  - Agregaciones, `groupby`, consultas y visualización básica

## Requisitos
- Python 3.9 o superior
- Dependencias principales:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `jupyter`

Puedes instalar todo con el archivo `requirements.txt` incluido.

## Cómo usar

### Opción A: Google Colab (recomendada)
- Ambos notebooks incluyen botón “Open in Colab”.
- Alternativamente, sube los `.ipynb` a Colab o ábrelos desde GitHub.

### Opción B: Ejecución local con Jupyter
1. Crea y activa un entorno virtual (opcional pero recomendado).
2. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Inicia Jupyter:
   ```bash
   jupyter notebook
   ```
4. Abre el notebook deseado y ejecuta las celdas.

## Datos utilizados
- Inmuebles CDMX: `alquiler.csv` (se carga desde URL en el notebook)
  - https://gist.githubusercontent.com/ahcamachod/a572cfcc2527046db93101f88011b26e/raw/ffb13f45a79d31223e645611a119397dd127ee3c/alquiler.csv
- Desafío alumnos: `alumnos.csv` (se carga desde URL en el notebook)
  - https://gist.githubusercontent.com/ahcamachod/807a2c1cf6c19108b2b701ea1791ab45/raw/fb84f8b2d8917a89de26679eccdbc8f9c1d2e933/alumnos.csv

## Estructura del proyecto
- `Copia_de_Python_para_Data_SCIENCE.ipynb`
- `inmuebles_CDMX.ipynb`
- `README.md`
- `requirements.txt`

## Notas
- En Colab puede aparecer instalación de paquetes con `pip` dentro del notebook a modo de ejemplo. Si trabajas localmente, usa `requirements.txt` para mantener versiones compatibles.


## Licencia
- Proyecto para fines educativos y de práctica.
