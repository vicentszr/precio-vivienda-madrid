# ¿Es razonable el precio de esta vivienda?

Proyecto individual de **Fundamentos de la Ciencia de Datos** (Universidad Alfonso X el Sabio, curso 2026/27).

## Problema de negocio

Una persona que quiere comprar una vivienda en Madrid capital necesita saber si el precio de un anuncio es razonable y si le conviene negociar, descartarlo o comprarlo, comparándolo con viviendas similares.

## Preguntas

1. ¿En qué porcentaje se desvía el precio/m² de un anuncio respecto a la mediana de su distrito y tramo de superficie (75-100 m²), y a partir de qué desviación conviene negociar, descartar o comprar?
2. ¿Cuánto se diferencia el precio/m² mediano de los distritos céntricos del de los periféricos, y compensa pagar más por el centro?
3. ¿Cuánto menor es el precio/m² mediano de un bajo frente a una planta alta, y es razonable aceptar un bajo por esa diferencia?

## Datos

- **Fuente:** [Precios y Características de Viviendas en Venta en Madrid Capital (noviembre 2024)](https://doi.org/10.5281/zenodo.14617870), Zenodo (CC BY 4.0). Autores: Lucia Hierro Quintero y Daniel Barrios Sánchez.
- **Tamaño:** 1.636 filas y 10 columnas.
- **Archivo:** `data/fotocasa_Madrid_datos_finales.csv`.

## Contenido del repositorio

- `analisis_vivienda.ipynb`: cuaderno con todo el análisis de la Entrega 1 (carga, EDA, problemas de los datos y respuestas a las tres preguntas).
- `data/`: datos originales.
- `figuras/`: gráficos generados por el cuaderno.

## Cómo ejecutarlo

1. Instalar las dependencias: `pip install pandas matplotlib seaborn jupyter`.
2. Abrir `analisis_vivienda.ipynb` (por ejemplo, en Visual Studio Code).
3. Ejecutar todas las celdas de arriba abajo (Restart & Run All). Las figuras se guardan en `figuras/`.

## Resultados principales (Entrega 1)

- **Pregunta 1:** la desviación del precio/m² respecto a la mediana de su distrito tiene mediana 0 %; la mitad de las viviendas está entre -16,5 % y +18,7 %.
- **Pregunta 2:** en viviendas de 75 a 100 m², la mediana es de 7.862 €/m² en los distritos céntricos y de 2.654 €/m² en los periféricos (un 196,2 % más).
- **Pregunta 3:** los bajos son más baratos por m² que las plantas altas, con un -17,1 % en menos de 75 m² y un -46,9 % en más de 100 m²; el tramo de 75 a 100 m² es el menos concluyente.

## Tecnología

Python, pandas, matplotlib, seaborn y Jupyter Notebook (Visual Studio Code).

## Estado

Entrega 1 completada (27 de noviembre de 2026). Entrega 2: 15 de enero de 2027.

## Autor

Vicente Sánchez Reza
