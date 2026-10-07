# Sole Economics: dashboard de rentabilidad del mercado de reventa de zapatillas

Dashboard interactivo que analiza la rentabilidad, la volatilidad y la demanda del mercado de reventa de zapatillas en 2023, con 2.000 modelos y 18 variables de StockX.

Proyecto individual del curso de Visualización de Datos (Fundación Universitaria Compensar, 2026).

🔗 **Ver el dashboard:** https://jhojangomez448.github.io/sole-economics/

## Qué responde

> ¿De qué manera el volumen de ventas y la volatilidad influyen en el margen de ganancia de las zapatillas?

El dashboard tiene 4 pestañas:

1. **Panorama del mercado:** indicadores generales y distribución de marcas.
2. **Rentabilidad:** margen por marca, precio de lanzamiento frente a precio de reventa.
3. **Volatilidad y demanda:** relación entre ventas, volatilidad, ofertas de compra y de venta.
4. **Oportunidades:** ranking de los modelos más rentables y clasificación por cuadrante.

Incluye filtros por marca, gráficos de barras, dispersión y dona, y una tabla interactiva.

## Algunos hallazgos

- Alrededor del **70 %** de los modelos se vende por encima de su precio de lanzamiento, y el margen mediano ronda el **20 %**.
- El volumen de ventas casi no explica el margen (correlación de **0,036**), y la volatilidad tampoco muestra una relación lineal relevante con él (**-0,038**).
- Las marcas líderes (Nike, Jordan, Adidas) venden más unidades por modelo que el resto (unas 60 frente a unas 37), con márgenes medianos similares.
- Adidas combina un margen mediano cercano al **31 %** con unas **83** ventas promedio por modelo.
- Las colaboraciones de Jordan con Travis Scott y Off-White lideran el ranking, con márgenes de más de 1.000 %.

## Tecnologías

HTML · CSS · JavaScript · Chart.js

El análisis completo está en el [informe en PDF](Informe_Sole_Economics.pdf).

## Archivos

```
├── index.html                      # El dashboard (se abre en el navegador)
├── sneakers2023.csv                # Datos usados
└── Informe_Sole_Economics.pdf      # Informe del proyecto
```

## Cómo verlo

Entra al enlace de arriba, o descarga `index.html` y ábrelo en tu navegador. Necesita conexión a internet para cargar Chart.js y las fuentes.

## Datos

Los datos provienen del dataset público *Sneaker Resale Data 2023: StockX Marketplace Insights* (Perez, S., 2023), publicado en Kaggle y construido a partir de registros de StockX: https://www.kaggle.com/datasets/ajiaron/stockx-sneaker-data

Los datos pertenecen a sus autores originales y se incluyen aquí solo con fines educativos.

## Autor

Jhojan Zambrano · [GitHub](https://github.com/JhojanGomez448)
