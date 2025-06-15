🏷️[Abrir Proyecto](https://github.com/JorgeRivero1/EDA_API_ALPHAVANTAGE/blob/main/EDA_API_ALPHAVANTAGE.ipynb)
# 📊 EDA_API_ALPHAVANTAGE

🔍 _Análisis Exploratorio de Datos del Mercado Bursátil usando la API de Alpha Vantage_

---

## 🧠 Descripción del Proyecto

Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** de acciones de algunas de las empresas tecnológicas más importantes del mercado: **Microsoft (MSFT)**, **Apple (AAPL)**, **Google (GOOGL)** y **Amazon (AMZN)**.  
📡 Los datos se obtienen mediante solicitudes a la **API de Alpha Vantage**, una plataforma que ofrece información financiera en tiempo real.

🎯 El objetivo del análisis es explorar y visualizar cómo han evolucionado los **precios de cierre ajustados** de estas acciones desde **2018**, identificar patrones y comparar su rendimiento a lo largo del tiempo.

---

## 🛠️ Herramientas Utilizadas

- 🔑 **Alpha Vantage**: Para obtener los datos financieros mediante su API.  
- 🐍 **Python + Jupyter Notebook**: Para el procesamiento, análisis y visualización.  
- 🧮 **Pandas**: Para la manipulación de datos tabulares.  
- 📈 **Matplotlib y Seaborn**: Para la creación de gráficos y visualizaciones atractivas.  

---

## 🎯 Objetivos del Análisis

- 📥 Obtener datos bursátiles reales de empresas tecnológicas.  
- 🧹 Preparar los datos para su análisis y visualización.  
- 📊 Visualizar el comportamiento del precio de cierre ajustado a lo largo del tiempo.  
- 📊 Comparar el rendimiento entre las distintas empresas.  
- 🔍 Identificar posibles patrones o tendencias relevantes.  

---

## 💡 Valor que aporta el proyecto

Este análisis ofrece una visión **clara y comprensible** del comportamiento bursátil de algunas de las empresas más influyentes del mundo. Puede servir como base para:

- 💰 Tomar decisiones informadas sobre inversión.  
- 🧪 Practicar técnicas de análisis de datos con fuentes externas.  
- 🎓 Aplicar conocimientos de análisis exploratorio a datos financieros reales.  

---

## 🔎 ¿Qué se hace paso a paso?

1. **📌 Selección de empresas a analizar**  
   Se eligen cuatro grandes compañías del sector tecnológico cuyas acciones cotizan en el mercado bursátil. Estas empresas se seleccionan por su relevancia, tamaño e impacto en los mercados globales.

2. **🌐 Obtención de datos con la API de Alpha Vantage**  
   Se hace una petición a la API para cada empresa. Esto devuelve un histórico de precios diarios, incluyendo apertura, cierre, volumen y especialmente el **precio de cierre ajustado**, que refleja mejor el valor real de una acción al considerar dividendos y splits.

3. **🧼 Transformación y limpieza de los datos**  
   Se convierte la información obtenida en tablas ordenadas y se limpian los datos innecesarios. Solo se conservan las columnas relevantes y se filtran los registros desde el año **2018**.

4. **🔗 Unificación de la información**  
   Los datos de las cuatro empresas se integran en un único conjunto. Esto permite crear gráficos comparativos que muestran la evolución simultánea de todas las acciones.

5. **📉 Visualización de la evolución de las acciones**  
   Se crean gráficos que muestran cómo han variado los precios de las acciones a lo largo del tiempo. Esto ayuda a detectar momentos clave de crecimiento o caída.

6. **⚖️ Análisis comparativo**  
   Se observa y analiza cómo se comportan las acciones entre sí. Por ejemplo:

   - ¿Cuál tuvo un crecimiento más estable?  
   - ¿Cuál presentó mayor volatilidad?  
   - ¿Coincidieron en alguna tendencia general?

---
