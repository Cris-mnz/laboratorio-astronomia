# Arqueología Galáctica con Gaia DR3

Este proyecto utiliza datos reales del satélite **Gaia (DR3)** para procesar, filtrar y mapear los ciclos de vida de las estrellas en nuestra galaxia.

## Estructura del Notebook (`Gaia_HR.ipynb`)

El análisis está organizado de forma progresiva en varias celdas de Jupyter de la siguiente forma:

1. **Diagrama HR Base:** Ploteo masivo utilizando datos filtrados de Gaia DR3 (el filtro consiste en eliminar celdas vacías).
2. **Diagrama HR con mapa de color:** El mismo ploteo, solo que ahora se añade una normalización de color que refleje los colores y temperaturas de las estrellas. Además, está ploteado el Sol.
3. **El Vecindario Cercano ($\alpha$ Centauri A):** Incorporación de Alfa Centauri A junto al Sol para comparar de forma gráfica cómo se posicionan las estrellas de nuestro entorno local frente a las poblaciones globales de la galaxia.
4. **Población estelar:** Ahora el diagrama se divide en dos grandes grupos: las estrellas de Población I y Población II (Con índices de metalicidad [Fe/H] > -0.2 y [Fe/H] < -1.0 respectivamente).
### Tecnologías Utilizadas

* **Python 3** (Jupyter Notebooks)
* **Pandas** & **NumPy** para el manejo de grandes volúmenes de datos.
* **Matplotlib** para la visualización de datos.