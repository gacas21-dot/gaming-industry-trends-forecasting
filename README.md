# Pronóstico de Tendencias y Éxito Comercial: Mercado Global de Videojuegos 🎮

## 🎯 Objetivo del Proyecto
El objetivo principal es identificar los patrones que determinan el éxito de un videojuego para planificar la estrategia comercial de la tienda "Ice" para el año 2017. Este análisis permite minimizar riesgos en la gestión de inventario y optimizar la asignación de presupuesto publicitario.

## 📊 Habilidades Técnicas y Metodología
* **Análisis de Ciclo de Vida:** Determinación del tiempo de vigencia de las consolas (promedio de 10 años) para identificar el "periodo rentable" de inversión.
* **Análisis Regional (NA, EU, JP):** Modelado de perfiles de usuario por región, detectando variaciones críticas en preferencias de género y clasificación ESRB.
* **Estadística Inferencial:** * Pruebas de hipótesis (t de Welch) para comparar calificaciones de usuarios entre plataformas (Xbox One vs. PC).
    * Análisis de correlación de Pearson para medir el impacto de la crítica profesional en las ventas globales.
* **Visualización de Datos:** Uso de diagramas de caja (boxplots) para analizar la dispersión de ventas y mapas de calor para correlaciones.

## 🚀 Hallazgos Estratégicos
1. **Líderes de Mercado:** PS4 y Xbox One se identificaron como las plataformas más rentables para el periodo 2017.
2. **Influencia de Reseñas:** Se demostró que las reseñas de críticos profesionales tienen una correlación moderada con las ventas, mientras que las de los usuarios tienen un impacto mínimo en el éxito comercial inicial.
3. **Divergencia Cultural:** El mercado japonés muestra una preferencia única por el género RPG y consolas portátiles (3DS), a diferencia de Occidente donde predominan los géneros de Acción y Shooter.

## 🛠️ Stack Tecnológico
* **Python:** Pandas, NumPy.
* **Visualización:** Matplotlib, Seaborn.
* **Estadística:** SciPy (Análisis de hipótesis y métricas de efecto como Hedges’ g).

---
## 📂 Estructura del Repositorio
* `proyecto_ice_2013_2016.ipynb`: Notebook con el análisis completo.
* `Datasets/`: Carpeta con el archivo `games.csv` (Datos históricos hasta 2016).
* `requirements.txt`: Dependencias del proyecto.
