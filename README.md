# ml-aprendizaje
Ruta de aprendizaje de Machine Learning - EDA y análisis de datos financieros
# EDA — Precios del Oro 2020-2024

Análisis exploratorio de datos (EDA) sobre precios históricos 
del oro usando Python, pandas y matplotlib.

## Qué contiene este análisis
- Descarga de datos reales desde Yahoo Finance (yfinance)
- Estadísticas descriptivas: media, volatilidad, máximos y mínimos
- Visualización del precio histórico 2020-2024
- Análisis de retornos diarios y distribución
- Mapa de correlaciones entre variables OHLCV
- Construcción de features: medias móviles MA7, MA21, MA50, MA200

## Tecnologías
Python | pandas | NumPy | matplotlib | yfinance

## Conclusiones principales
- Retorno promedio diario: 0.048%
- Volatilidad diaria: 1.02%
- Mejor día: +5.95% | Peor día: -4.98%
- Close, High, Low y Open tienen correlación >0.99 entre sí
- El volumen no correlaciona con el precio (r=-0.01)
- 
## Proyectos completados

### Etapa 0 — EDA Precios del Oro
Análisis exploratorio completo con estadísticas, visualizaciones y correlaciones.

### Etapa 1 — Matemáticas aplicadas a ML  
Álgebra lineal, estadística y cálculo aplicados a datos financieros reales.

### Etapa 2 — ML Clásico
Regresión lineal y Random Forest con features externas (DXY, VIX, S&P500).
R² mejoró 4x al agregar variables macroeconómicas.

### Proyecto — Gold Direction Predictor
Clasificador para predecir dirección del oro. Conclusión honesta: 
el mercado es mayormente eficiente, el edge predecible es pequeño (~2-8% R²).
Las limitaciones del modelo demuestran criterio analítico real.
