# Actividad: MLOps Stack Canvas y AIOps

## 1. MLOps Stack Canvas
El MLOps Stack Canvas es un marco de trabajo que nos permite visualizar la madurez de un proyecto de Machine Learning, dividiéndolo en capas:
- **Data Engineering:** Ingesta, validación y almacenamiento de datos.
- **Model Development:** Experimentación, entrenamiento y versionado.
- **Orchestration:** Automatización de pipelines (CI/CD/CT).
- **Serving & Monitoring:** Despliegue del modelo y vigilancia de su rendimiento en producción para evitar el model drift.

## 2. Definición de AIOps
AIOps (Artificial Intelligence for IT Operations) es el uso de IA y Machine Learning para automatizar las operaciones de TI. Se enfoca en analizar logs, métricas y eventos en tiempo real para predecir fallos y optimizar la infraestructura tecnológica.

## 3. Relación entre MLOps y AIOps
La relación es fundamental: **MLOps actúa como el motor que crea y mantiene los modelos**, mientras que **AIOps actúa como el consumidor que utiliza dichos modelos para gestionar la infraestructura**. 
Sin MLOps, los modelos usados en AIOps serían inestables y difíciles de actualizar; sin AIOps, MLOps carecería de una visibilidad profunda sobre el estado de los sistemas donde se ejecutan los modelos. Es un ciclo de mejora continua.
