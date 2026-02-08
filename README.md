# 📉Desviación Sectorial de la Media

Bandas de Bollinger Sectoriales Simplificadas

## 📌Descripción del proyecto

Este proyecto detecta sectores completos del mercado que se encuentran en una condición de sobreventa extrema, midiendo cuán lejos está el precio promedio del sector respecto a su media móvil de 20 días (SMA 20), normalizado por su propia volatilidad.

El enfoque replica el concepto de Bandas de Bollinger, pero aplicado a nivel sectorial, no individual.

## 🧠Insight financiero

- ¿Qué sector tiene un precio promedio actual que está más de dos desviaciones estándar por debajo de su SMA 20?

Cuando un sector entero cae más de –2 desviaciones estándar, no se trata de ruido:
- Es venta forzada o pánico generalizado
- Aumenta la probabilidad de reversión a la media
- Señala oportunidades de rotación sectorial contraria

## 💼Valor de negocio

📊 Identifica oportunidades de compra sistémicas, no aisladas

🌍 Ideal para asset allocation y ETFs sectoriales

⚠️ Detecta excesos de mercado antes de rebotes violentos

## 🧠Reduce el riesgo de falsas señales individuales

Este análisis es clave para:
- gestores de portafolio
- estrategias macro
- trading cuantitativo de reversión

## 🗄️Tablas utilizadas

- tickers
- Información estructural (sector, ticker)
- precios_diarios
- Precios OHLC diarios
- indicadores_tecnicos
- Fechas y alineación temporal

## ⚙️Metodología

- Agregación sectorial diaria
- Se calcula el precio promedio del sector por día
- Cálculo de SMA 20 sectorial
- Media móvil de 20 períodos del precio promedio del sector
- Cálculo de volatilidad sectorial
- Desviación estándar del precio promedio (20 períodos)
- Normalización del desvío
- (Precio actual − SMA 20) / Desviación estándar
- Filtro extremo
- Se seleccionan sectores con desvío < –2

## 📈Interpretación de resultados

Desvío cercano a 0 → Sector en equilibrio

Desvío entre –1 y –2 → Debilidad moderada

Desvío < –2 →
🔥 Sobreventa extrema
📉 Pánico sectorial
🔄 Alta probabilidad de reversión

## 🚀Posibles extensiones

- Confirmar señal con RSI sectorial
- Comparar contra flujo de volumen
- Analizar performance post-señal (5, 10, 20 días)
- Aplicar el mismo modelo a industrias o países
- Construir un ranking dinámico de estrés sectorial

## 🧩Conclusión

- Este proyecto transforma el concepto clásico de Bandas de Bollinger en una herramienta macro de timing sectorial, ideal para detectar momentos donde el mercado exagera el castigo y abre oportunidades asimétricas.
- Es análisis técnico… pero a nivel sistémico.

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
