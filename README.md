# ClientChurn
Data Science Project to Analyze Client Churn

# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

Este proyecto tiene como objetivo explorar, entender y anticipar el comportamiento de evasión de clientes en **Telecom X**, una empresa de telecomunicaciones ficticia con información realista sobre contratos, servicios y facturación.

A través del análisis de datos históricos proporcionados en formato JSON, se llevó a cabo un proceso completo de:

- 🔍 **Exploración de datos** (EDA)
- 🧹 **Limpieza y transformación de columnas anidadas**
- 📈 **Visualización de patrones de cancelación**
- 🧠 **Identificación de variables clave que impactan el churn**

El enfoque principal estuvo en descubrir **qué características o comportamientos están más asociados a la cancelación del servicio**, como el tipo de contrato, el uso de servicios complementarios, el método de pago, entre otros.

## 📁 Contenido del proyecto

- `TelecomX_LATAM.ipynb`: Notebook principal con todo el flujo de análisis, visualizaciones y conclusiones.
- `TelecomX_diccionario.md`: Diccionario de datos con la descripción de todas las columnas del dataset.
- `TelecomX_Analisis_Churn_Estructura.ipynb`: Estructura inicial del reto.
- Datos importados directamente desde:  
  `https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json`

## 📌 Resultados destacados

- Los contratos mensuales presentan tasas de evasión significativamente más altas.
- Clientes que no utilizan servicios como `Tech Support` o `Online Security` son más propensos a cancelar.
- El tiempo de contrato (`tenure`) y el gasto total (`Charges.Total`) son buenos predictores del churn.

## ✅ ¿Por qué es importante?

Anticipar la evasión permite a las empresas de telecomunicaciones **tomar decisiones proactivas**, reducir la pérdida de clientes y mejorar la experiencia del usuario mediante acciones dirigidas de fidelización.

---

📬 *Para más detalles o colaboraciones, puedes abrir un issue o forkear este repositorio.*
