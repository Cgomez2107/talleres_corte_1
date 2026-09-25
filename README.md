# Talleres Corte 1 - Algoritmos de Búsqueda e Inteligencia Artificial

## Integrantes

- Carlos Alberto Gomez Posada
- Jhon Hander Patiño Londoño

## Descripción breve de la actividad

Este repositorio contiene los talleres del primer corte de la asignatura Sistemas Inteligentes I. La actividad estudia la representación de problemas como espacios de estados y la aplicación de algoritmos de búsqueda, heurísticas y estrategias de decisión para resolver problemas de inteligencia artificial.

## Estructura y relación de notebooks

| Notebook | Contenido |
| --- | --- |
| `Resolucion_Problemas_Busqueda_NoInformada.ipynb` | Búsqueda no informada mediante BFS y DFS, con comparación de sus recorridos y costos. |
| `Resolucion_Problemas_Busqueda_Informada.ipynb` | Búsqueda de Costo Uniforme, A* y Beam Search usando costos y funciones heurísticas. |
| `Minimax.ipynb` | Aplicación del algoritmo Minimax para la toma de decisiones en juegos. |
| `Poda_Alfa_Beta.ipynb` | Optimización de Minimax mediante poda Alfa-Beta. |

Los notebooks principales se encuentran en la carpeta `notebooks/`. Adicionalmente, en `results/Resolucion_Problemas_Busqueda_Informada.ipynb` se encuentra el desarrollo de la actividad práctica de búsqueda informada sobre una cuadrícula, con comparación de Costo Uniforme, A* y Beam Search para diferentes valores de `k`.

## Instrucciones de ejecución

### Requisitos

- Python 3.10 o superior.
- Jupyter Notebook o JupyterLab.
- Las librerías indicadas en cada notebook.

### Pasos

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/Cgomez2107/talleres_corte_1.git
   cd talleres_corte_1
   ```
2. Crear y activar un entorno virtual:

   ```bash
   python -m venv .venv
   ```

   En Windows:

   ```bash
   .venv\Scripts\activate
   ```

   En macOS o Linux:

   ```bash
   source .venv/bin/activate
   ```
3. Instalar Jupyter y las dependencias requeridas:

   ```bash
   python -m pip install --upgrade pip
   pip install jupyter matplotlib
   ```
4. Iniciar Jupyter:

   ```bash
   jupyter notebook
   ```
5. Abrir y ejecutar los notebooks ubicados en `notebooks/`, ejecutando sus celdas en orden. También puede abrirse el notebook ubicado en `results/` para consultar el desarrollo de la actividad de búsqueda informada.

## Uso de IA Generativa

La inteligencia artificial generativa se utilizó como herramienta de apoyo durante el desarrollo del trabajo, principalmente para:

- orientar la explicación de los conceptos de búsqueda, heurísticas, Minimax y poda Alfa-Beta;
- apoyar la organización y redacción de algunas secciones de los notebooks y de este README;
- sugerir y revisar implementaciones, ejemplos y comparaciones de resultados;
- detectar posibles errores y proponer mejoras en el código.

Las decisiones finales, la adaptación del código al problema y la verificación de la ejecución corresponden a los integrantes del trabajo.
