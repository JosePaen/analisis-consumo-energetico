# ✅ Análisis de Consumo Eléctrico en Edificios

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre el consumo energético de edificios utilizando **Python y Pandas**.  
El objetivo es identificar patrones de consumo y entender qué factores influyen más en la demanda eléctrica.

---

## ✅ Objetivos del análisis

El estudio responde tres preguntas principales:

1. **¿En qué meses el consumo energético es más alto?**
2. **¿Qué tipo de edificación consume más energía por metro cuadrado?**
3. **¿Las variables climáticas influyen en el consumo eléctrico?**

---

## ✅ Dataset

El dataset incluye:

- Lecturas horarias de energía  
- Características de edificios  
- Variables climáticas  
- Uso principal de cada inmueble  
- Mediciones en cuatro medidores distintos: **m0, m1, m2 y m3**

📌 **Importante:** Los datos provienen del **hemisferio norte**.  
Por esa razón, los meses de mayor consumo corresponden al invierno de esa región (**junio–septiembre en el dataset**).

---

## ✅ Proceso ETL (Resumen)

✔ Renombrado de columnas para facilitar lectura  
✔ Imputación de valores nulos  
✔ Conversión de fechas desde timestamp  
✔ Creación de columnas temporales (mes, hora, día)  
✔ Cálculo de consumo por metro cuadrado para cada medidor

---

## ✅ Resultados del EDA

### ✅ 1. ¿En qué meses se consume más energía?

Tras agrupar el consumo por mes, se observa que:

- El mayor consumo ocurre entre **junio y septiembre**
- El pico máximo se registra en **agosto**

✅ Esto coincide con el invierno del hemisferio norte, donde aumenta el uso de calefacción y climatización.

---

### ✅ 2. ¿Qué tipo de edificio consume más energía por m²?

Comparando el consumo promedio por tipo de uso:

| Tipo de edificio | Consumo por m² |
|------------------|----------------|
| Utility | Más alto |
| Retail | Elevado por horarios y climatización |
| Residencial / Oficinas / Educación | Moderado |
| Estacionamientos y templos | Muy bajo o casi nulo |

✔ Algunos tipos de edificios requieren más potencia y funcionamiento continuo.

---

### ✅ 3. ¿Influye el clima en el consumo eléctrico?

Se analizaron correlaciones con:

- Temperatura del aire  
- Viento  
- Presión  
- Nubosidad  
- Precipitación  

📌 **Las correlaciones fueron muy bajas**, indicando que:

➡ El consumo depende más del tipo de edificio, su equipamiento y actividad  
y no tanto de las condiciones climáticas.

---

## ✅ Conclusión final

- Existe un **patrón estacional**: el invierno del hemisferio norte presenta el mayor consumo.  
- Los edificios **Utility** son los más demandantes por m².  
- El clima no explica de forma significativa el consumo eléctrico.  
- El análisis puede servir como base para **futuros modelos predictivos o propuestas de eficiencia energética**.

---

## ✅ Tecnologías utilizadas

- Python  
- Pandas  
- Google Colab
- GitHub

---

## ✅ Autor

📍 **Jose Audicio**  
📌 Proyecto Informatorio - Data Analytics  
📅 **Año: 2025**

---

