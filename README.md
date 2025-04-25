# P7
# 🪙 Lanzar una Moneda - Simulación Interactiva

Esta aplicación web permite simular el lanzamiento de una moneda y visualizar el comportamiento de la media de resultados a lo largo de múltiples experimentos. La aplicación está desarrollada con **Streamlit**, una biblioteca de Python para construir interfaces web de forma rápida y sencilla.

## 🎯 Funcionalidad

La app simula el lanzamiento de una moneda justa (cara o cruz) durante un número determinado de iteraciones. Cada experimento calcula la media de los resultados (con cara = 1 y cruz = 0), y permite visualizar cómo la media se aproxima al valor teórico esperado (0.5) a medida que se incrementan las iteraciones, ilustrando así la Ley de los Grandes Números.

Cada vez que el usuario ejecuta un nuevo experimento, se guarda un registro de los resultados, lo que permite comparar diferentes ejecuciones.

## 📊 Gráficos utilizados

- **Gráfico de línea de medias por experimento:** muestra cómo varía la media de resultados entre cada experimento.
- **Histograma (opcional):** para visualizar la distribución de resultados en un solo experimento (si decides agregarlo).
- **Elementos interactivos:** controles para definir el número de iteraciones y botones para ejecutar experimentos.

## 🧰 Librerías utilizadas

- [`pandas`](https://pandas.pydata.org/): para la manipulación de datos.
- [`scipy`](https://scipy.org/): (opcional) para cálculos estadísticos adicionales.
- [`streamlit`](https://streamlit.io/): para construir la interfaz web.
- [`time`](https://docs.python.org/3/library/time.html): para gestionar pausas o medir duración (si se usa).

## 🚀 Cómo ejecutar

1. Clona este repositorio:

```bash
git clone https://github.com/YamelLpz/P7.git
cd P7