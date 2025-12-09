# Business Intelligence (BI) para Gestión de Personas: Del Dato a la Decisión Estratégica en RR.HH.

Este proyecto demuestra la aplicación de **Business Intelligence (BI)** en un escenario de **Gestión de Personas**. Realizado como desafío final de la formación en Big Data, el objetivo central fue transformar una base de **datos ficticios** de una encuesta de bienestar de 100 colaboradores en una herramienta de gestión estratégica para la toma de decisiones ejecutivas de RR.HH.

El proyecto cubrió el ciclo completo de análisis: tratamiento de datos (en Excel), modelado y creación de un **Dashboard Interactivo en Power BI**, y la elaboración de una **Presentación Ejecutiva** enfocada en los *insights*.

El análisis cruzado de datos reveló la **correlación directa** entre calidad del sueño y productividad (energía y concentración), identificando el **modelo de trabajo Presencial** como el de mayor riesgo de sobrecarga. Con base en los hallazgos, se definieron tres recomendaciones estratégicas que se centran en la **Focalización de Recursos** y la **Protección de la Desconexión**, garantizando un retorno medible sobre la inversión en iniciativas de bienestar corporativo.

---

## 1. Introducción y Tarea de Negocios 

Este proyecto es un estudio de caso práctico enfocado en la **transformación de datos de bienestar en valor estratégico** para la empresa. El objetivo es **desarrollar una estrategia de RR.HH. basada en datos** que priorice la salud y la energía del colaborador.

La dirección ha identificado que la **mitigación del riesgo de *burnout*** y la optimización de la **capacidad cognitiva** de la plantilla son cruciales para la productividad y la retención de talentos a largo plazo. El propósito es reemplazar las intervenciones de bienestar genéricas por acciones **focalizadas y con ROI mensurable**.

---

## 2. Preguntas Clave de Negocios 

Para guiar el análisis y asegurar que los resultados fueran accionables, este proyecto se centró en responder las siguientes preguntas estratégicas:

1.  **¿Cuál es el principal factor de bienestar que impacta directamente la capacidad cognitiva (energía, concentración y ánimo) de la plantilla?**
2.  **¿Cuáles son los principales *clusters* de riesgo (por modalidad o departamento) que presentan mayor dificultad en mantener un ritmo de trabajo sostenible y equilibrado?**
3.  **¿Existe una disparidad significativa en el bienestar y la carga de trabajo entre géneros o grupos demográficos que exija una auditoría de equidad e intervención dirigida?**
4.  **¿Dónde deben enfocarse los recursos e inversiones en iniciativas de bienestar para garantizar el máximo Retorno sobre la Inversión (ROI) para el negocio?**

---

## 3. Preparación de los Datos 

El análisis utilizó una base de **datos ficticios** de una encuesta de bienestar, simulando un escenario real de gestión de personas. Los datos representan las respuestas de 100 colaboradores a un cuestionario estructurado.

### Fuentes de Datos y Estructura

* **Fuente:** **Datos Ficticios** de una Encuesta de Bienestar (100 colaboradores) del reto final de la formación en Big Data.
* **Variables Clave Analizadas:** El *dataset* contenía 18 campos, siendo los más relevantes:
    * `Calidad del sueño (1-10)`, `Nivel de energía diaria (1-5)`, `Estado de ánimo (1-5)`
    * `Tiempo para desconectar (1-10)`, `Ritmo de trabajo sostenible (Sí/No)`, `Recuperación emocional (1-5)`
    * `Modalidad` (Remoto, Híbrido, Presencial), `Departamento`, `Género`.
* **Consideraciones:** El uso de datos ficticios permitió una exploración completa del proceso de análisis, desde la limpieza hasta la entrega de la estrategia.

### Entregable

El resultado de esta fase es el archivo de datos base: **`dataset_respuestas_100_empleados.xlsx`** (o su versión CSV).

---

## 4. Limpieza y Creación de Datos Analíticos 

Esta fase se centró en la preparación y el modelado de los datos dentro del entorno de Power BI para crear métricas de análisis cruciales.

### Herramientas y Metodología

| Tarea Principal | Herramienta Elegida | Justificación |
| :--- | :--- | :--- |
| **Limpieza y Transformación** | **Excel / Power BI (Query Editor)** | Tratamiento inicial de la base de datos (coherencia de tipos, gestión de nulos) y carga en el modelo de datos. |
| **Modelado y Métricas** | **Power BI (DAX)** | Creación de medidas (DAX) para calcular promedios, medianas, y *scores* agregados por segmento (departamento/modalidad), esenciales para la comparación de riesgos. |

### Entregable

El resultado de esta fase es el archivo del modelo de datos cargado en Power BI: **`Retos - Grupo 1v2.pbix`**.

---

## 5. Análisis de Datos e Insights 

Esta sección consolida los descubrimientos a través de la exploración del Dashboard Interactivo, respondiendo directamente a las preguntas de negocio.

| Agregación Realizada | Enfoque Analítico | Objetivo Analítico |
| :--- | :--- | :--- |
| **Correlación de Sueño** | `Calidad del Sueño` vs. `Energía / Concentración` | Medir la dependencia y validar el impacto del descanso en la productividad. |
| **Riesgo por Modalidad** | `Tiempo para desconectar` por `Modalidad` | Identificar el riesgo de sobrecarga asociado a modelos de trabajo específicos (Presencial/Híbrido). |
| **Riesgo Operacional** | Métricas de bienestar por `Departamento` | Localizar los **clusters de riesgo** para focalizar la intervención. |
| **Disparidades de Género** | `Calidad del Sueño` y `Sentido del Trabajo` por `Género` | Detectar brechas de equidad y desalineamientos estratégicos. |

### Descubrimientos Clave (Respuesta a Preguntas de Negocio)

La principal conclusión es que el **bienestar es una inversión directa en la capacidad cognitiva**, con riesgos claramente localizados:

* **1. El Factor Crítico:** La **Calidad del Sueño** es el motor principal más fuerte de `Energía`, `Concentración` y `Estado de Ánimo`.
* **2. Riesgo de Sobrecarga:** El modelo **Presencial** y los colaboradores del departamento de **Operaciones** son los grupos más vulnerables a la falta de desconexión y al bajo `Ritmo de Trabajo Sostenible`.
* **3. Equidad:** Se identificaron disparidades de **género** que requieren una auditoría, afectando la calidad del sueño en mujeres y el sentido del trabajo en hombres.

