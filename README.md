# 🚨 Customer Churn Analysis - TelecomX LATAM

¡Bienvenido al análisis de **evasión de clientes** de una de las compañías de telecomunicaciones más importantes de LATAM!  
Este proyecto busca identificar los factores clave que llevan a los usuarios a cancelar sus servicios, utilizando técnicas de análisis de datos en Python.

---

## 🎯 Objetivo

Detectar patrones de **churn (evasión de clientes)** en los servicios de TelecomX mediante el análisis exploratorio de datos y visualizaciones interactivas.  
El objetivo es proporcionar **insights valiosos** que permitan a la empresa **reducir la pérdida de clientes** mediante decisiones basadas en datos.

---

## 📊 Tecnologías y Herramientas

- 🐍 Python 3
- 🧮 Pandas
- 📊 Plotly Express
- 📦 JSON (estructura de entrada de datos)
- 📓 Jupyter Notebook

---

## 🗃️ Dataset

- Fuente: `TelecomX_Data.json`
- Contenido: Información demográfica, tipo de servicios contratados, cargos, métodos de pago y campo objetivo `Churn`.
- Transformación: Se aplicó `json_normalize` para estructurar el archivo JSON en un DataFrame plano y se convirtieron campos monetarios a formato numérico.

---

## 🧠 Principales Descubrimientos

🔍 El análisis reveló los siguientes **factores asociados a la evasión**:

- Clientes con **internet de fibra óptica** tienen mayor tasa de churn.
- El uso de **"electronic check"** como método de pago se relaciona con más cancelaciones.
- Clientes **sin servicios de valor agregado** (como StreamingTV o OnlineSecurity) tienden a abandonar.
- **Cargos mensuales elevados** también están relacionados con mayor probabilidad de churn.

---

## 🚀 Recomendaciones Estratégicas

- Ofrecer **servicios adicionales gratuitos o con descuento** (seguridad, streaming) para fidelización.
- Incentivar el uso de **métodos de pago automatizados**.
- Establecer **alertas preventivas** para clientes en riesgo de evasión.
- Analizar de forma continua los segmentos de clientes según sus características y comportamiento.

---

## 📁 Estructura del Proyecto
- 📄 TelecomX_Data.json
- 📄 TelecomX_LATAM.ipynb
- 📄 README.md (este archivo)

---

👤 Autor
Olfer Andrés Uribe Palomino
Analista de Datos | Backend Developer | Ciencia de Datos

📧 Contacto: https://www.linkedin.com/in/olfer-andres-uribe-palomino
