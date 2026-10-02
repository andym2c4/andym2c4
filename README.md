# Andy Montes

**Data Science · Machine Learning · Ingeniería de datos**

Lima, Perú · [LinkedIn](https://www.linkedin.com/in/andymonteschunocca/)

Soy un profesional de datos y tecnología, bachiller en Ingeniería Mecatrónica por la Universidad Nacional de Ingeniería. Combino experiencia en automatización, integración de datos y productos digitales en Enseña Perú con formación especializada y proyectos aplicados de Machine Learning.

Me interesa conectar el análisis y los modelos con decisiones concretas: detectar fraude, priorizar revisiones y convertir fuentes dispersas en información útil. Busco oportunidades en **Data Science y Machine Learning** donde pueda aportar desde la preparación de datos hasta la implementación y comunicación de resultados.

## Proyectos destacados

### [GlobalBank — Detección de fraude](https://github.com/andym2c4/b12)

Proyecto académico del programa BREIT sobre detección de fraude en apertura de cuentas, desarrollado con el dataset Bank Account Fraud (BAF).

- **Modelado:** comparación de XGBoost y LightGBM con modelos de referencia como regresión logística y LDA; selección de variables y calibración de probabilidades.
- **Evaluación:** partición fuera de tiempo (OOT), análisis de clases desbalanceadas y comparación entre detección de fraude y falsos positivos.
- **Implementación:** API con FastAPI que devuelve el score, la probabilidad calibrada y una banda de riesgo.

El [reporte publicado](https://github.com/andym2c4/b12/blob/main/reports/comparacion_modelos/ranking_modelos.csv) registra **ROC-AUC de 0.870 y Average Precision de 0.158** para XGBoost calibrado sobre 96,843 registros OOT, con 1.47% de prevalencia de fraude. Son resultados del conjunto de evaluación del proyecto.

[Comparación de modelos](https://github.com/andym2c4/b12/blob/main/notebooks/comparacion_modelos.ipynb) · [Código de la API](https://github.com/andym2c4/b12/blob/main/src/api/fraude_xgboost.py)

### [ASISTIA — Datos y asistencia docente para UGEL Luya](https://github.com/andym2c4/asistia-transferencia)

Aplicación para integrar fuentes de personal, calendarios y reportes de asistencia, revisar inconsistencias y generar consolidados mensuales trazables.

- **Datos:** importación de NEXUS y Excel, modelado en PostgreSQL y trazabilidad entre documentos, valores extraídos y correcciones.
- **IA aplicada:** extracción documental con Gemini e Isolation Forest para priorizar revisiones. El componente de anomalías es experimental y requiere evaluación independiente de campo.
- **Ingeniería:** aplicación web con Flask, migraciones SQL, pruebas automatizadas y documentación de instalación y operación.

[Arquitectura](https://github.com/andym2c4/asistia-transferencia/blob/main/docs/ARQUITECTURA.md) · [Modelo experimental](https://github.com/andym2c4/asistia-transferencia/blob/main/src/asistia/experimental/modelo.py) · [Pruebas](https://github.com/andym2c4/asistia-transferencia/tree/main/tests)

## Experiencia aplicada

En **Enseña Perú** he trabajado en automatización de procesos ETL, integración de plataformas, gobernanza de datos y levantamiento de requerimientos de Analytics/BI. Esta experiencia me permite conectar necesidades de los equipos con soluciones técnicas y acompañar su uso en la operación.

## Herramientas y métodos

| Área | Tecnologías y prácticas |
| --- | --- |
| Análisis y preparación de datos | Python, pandas, NumPy, SQL, Jupyter, análisis exploratorio |
| Machine Learning | scikit-learn, XGBoost, LightGBM, clasificación, detección de anomalías, evaluación y calibración |
| Ingeniería y desarrollo | PostgreSQL, ETL, FastAPI, Flask, Git, Docker, pytest |
| Visualización y BI | Matplotlib, Seaborn, Power BI, Looker Studio |

## Formación

- **Universidad Nacional de Ingeniería:** bachiller en Ingeniería Mecatrónica.
- **BREIT:** becario del Advanced Program in Data Science & Global Skills (2025–2026).
- **Formación MIT:** probabilidad, estadística y Machine Learning con Python.

**Idiomas:** español nativo e inglés avanzado.

Puedes contactarme por [LinkedIn](https://www.linkedin.com/in/andymonteschunocca/) para conversar sobre oportunidades en Data Science y Machine Learning.
