# Actividad: MLOps Stack Canvas y la Integración con AIOps

## 1. Descripción General
Este repositorio contiene el desarrollo del ejercicio enfocado en la comprensión del ciclo de vida de los sistemas de Machine Learning (ML) y su relación operativa con la Inteligencia Artificial aplicada a las operaciones de TI (AIOps). 

El trabajo se centra en el **MLOps Stack Canvas** como herramienta fundamental para la organización de proyectos de ML y la arquitectura que permite la sinergia entre el desarrollo de modelos y la gestión de infraestructura.

## 2. Componentes del Ciclo de Vida (MLOps)
El pipeline desarrollado en el diagrama adjunto abarca cuatro etapas críticas:
- **Data Ingestion & Prep:** Proceso de limpieza, normalización y *Feature Engineering* para garantizar datos de alta calidad.
- **Training & Validation:** Ejecución de pruebas de *backtesting* para asegurar que el modelo cumpla con los umbrales de precisión antes de cualquier despliegue.
- **Model Registry:** La "biblioteca" central que garantiza trazabilidad mediante el versionado de modelos, hiperparámetros y metadatos asociados.
- **Deployment (CI/CD/CT):** Implementación automatizada con capacidades de *Continuous Training* para mitigar la degradación del rendimiento en producción.

## 3. Definición de AIOps
AIOps (*Artificial Intelligence for IT Operations*) es la disciplina que integra tecnologías de IA y Machine Learning para automatizar la gestión de infraestructuras de TI. Su función principal es analizar flujos masivos de datos operativos (logs, métricas y telemetría) para detectar anomalías y realizar diagnósticos de causa raíz de manera eficiente.

## 4. Relación Estratégica: MLOps y AIOps
La integración se define bajo una relación simbiótica:
* **Proveedor (MLOps):** La fábrica que desarrolla, entrena y mantiene los modelos de inteligencia predictiva.
* **Consumidor (AIOps):** El motor operativo que utiliza dichos modelos para automatizar respuestas (como auto-escalado o parcheo de sistemas) sobre la infraestructura.

> **Nota:** La integración se visualiza en `image_0ddc76.jpg`, donde el *Model Registry* inyecta inteligencia al *AIOps Engine*, permitiendo que el sistema no solo reaccione a eventos, sino que los anticipe.

## 5. Estructura del Repositorio
- `s2026q2_z-mlops-SebastiànVaròn.drawio`: Archivo fuente del diagrama de arquitectura.
- `diagrama.png`: Versión exportada del diseño para visualización rápida.
- `README.md`: Documentación técnica del ejercicio.
