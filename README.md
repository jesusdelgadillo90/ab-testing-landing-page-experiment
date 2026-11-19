# Validando hipótesis de negocio con pruebas estadísticas — Experimento A/B en Landing Page

Evaluación estadística de un experimento A/B (`landing_experiment.csv`, versiones **A** y **B**) para determinar qué versión de la página de inicio conviene implementar, analizando **tasa de conversión**, **gasto promedio en usuarios convertidos** y comportamiento por **canal de tráfico**, **tipo de usuario**, **región** y **dispositivo**.

## 📂 Contenido del repositorio
* `landing_ab_experiment.ipynb` — *Notebook* con validación de datos, pruebas de hipótesis, análisis por segmentos, visualizaciones y recomendaciones de negocio.

## ▶ Cómo abrir y reproducir el análisis
1. Abre el archivo `.ipynb` directamente en GitHub o en **Google Colab**.
2. Ejecuta las celdas de arriba hacia abajo (requiere `pandas`, `numpy`, `scipy`, `statsmodels`, `matplotlib` y `seaborn`).
3. Revisa los resultados estadísticos (*estadístico de prueba*, *valor p* y tamaño/dirección del efecto) junto con las conclusiones de negocio.

## 💡 Preguntas clave abordadas
* ¿Existe diferencia significativa en el **gasto promedio por usuario convertido** (`converted == 1`) entre las versiones A y B?
* ¿Qué versión (**A** o **B**) logra mayor **tasa de conversión**?
* ¿Cómo influyen **`traffic_source`** y **`user_type`** (`Nuevo` vs. `Recurrente`) en la conversión?
* ¿Qué decisión y acciones recomiendan los datos para *marketing digital* y *landing page*?
