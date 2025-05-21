# Análisis del Funnel de Ventas para Fintech de Crowdfunding Inmobiliario

## 🚀 Introducción

Este proyecto presenta un análisis detallado del funnel (embudo) de ventas de una plataforma fintech de crowdfunding inmobiliario. El objetivo es identificar puntos clave de conversión, posibles cuellos de botella y áreas de oportunidad para optimizar el recorrido de los desarrolladores de proyectos, desde la solicitud inicial hasta el fondeo completo.

Aunque los datos utilizados en este análisis son **ficticios** (*dummy data*), la metodología y las técnicas aplicadas son representativas de un análisis real que buscaría generar insights accionables para mejorar la eficiencia y competitividad de la plataforma.

**[➡️ Ver el Notebook renderizado en nbviewer]https://nbviewer.org/github/JaimeEV/funnel_ventas/blob/main/funnel_ventas.ipynb)**
*(Recomendado para una lectura más amigable, especialmente si no estás familiarizado con los archivos .ipynb)*

**[📂 Ver el código fuente en GitHub](https://github.com/JaimeEV/funnel_ventas/blob/main/funnel_ventas.ipynb)**
*(Para revisar el código Python y la estructura del notebook)*

---

## 🎯 Objetivos del Análisis

* Identificar las diferentes etapas del funnel de ventas y cuantificar el número de proyectos en cada una.
* Analizar el tiempo promedio que transcurre entre las etapas críticas del funnel.
* Detectar posibles cuellos de botella o demoras significativas en el proceso.
* Explorar la distribución de los montos solicitados por los desarrolladores e identificar valores atípicos.
* Proponer ideas accionables basadas en los hallazgos para optimizar el funnel.

---

## 🛠️ Herramientas Utilizadas

* **Lenguaje de Programación:** Python
* **Librerías de Análisis de Datos:**
    * Pandas: Para la manipulación y limpieza de datos.
    * Matplotlib y Seaborn: Para la visualización de datos y generación de gráficas.

---

## 📊 Hallazgos Clave del Notebook

El análisis reveló varios insights importantes, entre ellos:

1.  **Estructura del Funnel:** Se mapearon las etapas desde la "Solicitud Recibida" hasta el "Fondeado Totalmente", observando la progresión y concentración de proyectos.
2.  **Tiempos de Procesamiento:**
    * Se identificó un tiempo promedio de **casi 7 días** para pasar de "Solicitud Recibida" a "Análisis de Viabilidad".
    * El paso a "Aprobado Comité" toma en promedio unos **15 días** desde la solicitud inicial.
    * Se analizó el impacto de la etapa "Información Adicional Solicitada" en los tiempos generales.
3.  **Montos Solicitados:**
    * La distribución de montos presenta un sesgo, con proyectos atípicos de alto valor, siendo el más elevado uno del sector "Tecnología".
4.  **Oportunidades de Optimización:**
    * Se discuten las implicaciones de los tiempos de espera en las primeras etapas y se proponen revisiones de procesos.
    * Se sugiere analizar los motivos de solicitud de información adicional para integrarlos más tempranamente en el funnel.

---

## 💡 Ideas Accionables Propuestas

* **Optimización del Análisis Inicial:** Investigar el flujo de trabajo entre la recepción de la solicitud y el análisis de viabilidad para reducir el tiempo de respuesta inicial.
* **Mejora en la Recopilación de Información:** Analizar las solicitudes de "información adicional" para identificar patrones y anticipar estos requerimientos desde el inicio, potencialmente rediseñando el formulario de solicitud inicial.
* **Gestión Diferenciada (Potencial):** Considerar si proyectos de muy alto monto o de ciertos tipos (ej. Tecnología) requieren un tratamiento o carril de análisis distinto.

---
## 🚀 Cómo Visualizar y Ejecutar el Notebook

1.  **Opción Recomendada (Visualización Rápida):**
    * Haz clic en el enlace de **nbviewer** proporcionado al inicio de este README para ver una versión renderizada y fácil de leer directamente en tu navegador.

2.  **Opción Técnica (GitHub y Entorno Local):**
    * Clona este repositorio: `git clone [https://github.com/JaimeEV/funnel_ventas.git]`
    * Asegúrate de tener Python y las librerías necesarias instaladas (pandas, matplotlib, seaborn, jupyter). Puedes crear un entorno virtual:
        ```bash
        python -m venv env
        source env/bin/activate  # En Windows: env\Scripts\activate
        pip install pandas matplotlib seaborn jupyter
        ```
    * Navega a la carpeta del proyecto y ejecuta Jupyter Notebook o JupyterLab:
        ```bash
        jupyter notebook
        # o
        jupyter lab
        ```
    * Abre el archivo `funnel_ventas.ipynb`.

---


