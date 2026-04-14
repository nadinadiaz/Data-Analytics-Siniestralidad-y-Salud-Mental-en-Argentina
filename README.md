# 📊 Análisis de Salud Mental, Estrés Económico y Siniestralidad Laboral en Argentina (2010–2024)

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Tidyverse](https://img.shields.io/badge/Tidyverse-white?style=for-the-badge&logo=tidyverse&logoColor=276DC3)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Descripción del Proyecto
Este estudio analiza la dinámica entre la **siniestralidad laboral**, el **bienestar psicológico** y el **contexto macroeconómico** argentino. A través de un enfoque longitudinal, el proyecto identifica cómo las crisis económicas y sanitarias (COVID-19) alteraron los patrones de riesgo laboral en el país.

---

## 🎯 Objetivos Estratégicos
* **Cuantificar** la evolución temporal de la siniestralidad y el malestar psicológico.
* **Evaluar** la correlación con variables de estrés económico e inflación.
* **Modelar** quiebres estructurales en el período post-pandemia.
* **Segmentar** hallazgos por grupos etarios para identificar vulnerabilidades específicas.

---

## 🧠 Hallazgos Clave (Insights)

| Hallazgo | Descripción |
| :--- | :--- |
| **Quiebre Post-2020** | Cambio de paradigma: la relación malestar-siniestralidad pasó de negativa a positiva. |
| **Factor Emergente** | Desde 2021, el malestar psicológico es un predictor relevante de accidentes físicos. |
| **Paradoja Económica** | Correlación inversa ($r \approx -0.75$): el estrés económico alto coincide con menor reporte de siniestros (posible subnotificación). |
| **Divergencia Etaria** | **Jóvenes:** Relación inversa (precarización). **Adultos:** Relación positiva moderada. |

---

## ⚙️ Metodología y Herramientas
El análisis se realizó íntegramente en **R**, aplicando las siguientes técnicas:
* **Normalización Estocástica:** Transformación a *Z-Scores* para comparar métricas de distinta naturaleza.
* **Análisis de Series Temporales:** Segmentación en Pre-pandemia (2010–2019) y Post-pandemia (2021–2024).
* **Tratamiento de Anomalías:** Identificación y aislamiento del año 2020 como outlier estructural.
* **Visualización Avanzada:** Implementación de `ggplot2` y `ggrepel` para una narrativa visual clara.

---

## 📂 Fuentes de Datos
* **SRT:** Superintendencia de Riesgos del Trabajo (Datos de siniestralidad).
* **UCA:** Observatorio de la Deuda Social (Indicadores psicosociales).
* **INDEC:** Índices macroeconómicos.

> [!IMPORTANT]
> **Limitaciones:** El estudio se centra en trabajadores cubiertos por ART, lo que representa un universo del empleo registrado, excluyendo el sector informal.

---

## 🚀 Cómo visualizar este proyecto
Puedes consultar el informe completo en formato interactivo aquí:
👉 [[Ver Presentación Ejecutiva (PDF)](https://nadinadiaz-github-io.vercel.app/docs/SiniestralidadLaboral.pdf)
---

## 👤 Autor
**Nadina Díaz** *Bioingeniera & Data Analyst* [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](TU_LINK_DE_LINKEDIN)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/nadinadiaz.github.io)

Data Analyst
