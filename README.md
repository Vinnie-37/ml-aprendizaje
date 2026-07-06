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
