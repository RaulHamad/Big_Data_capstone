---

# Spanish

---

# Business Intelligence (BI) para Gestión de Personas: Del Dato a la Decisión Estratégica en RR.HH.

Este proyecto demuestra la aplicación de **Business Intelligence (BI)** en un escenario de **Gestión de Personas**. Realizado como desafío final de la formación en Big Data, el objetivo central fue transformar una base de **datos ficticios** de una encuesta de bienestar de 100 colaboradores en una herramienta de gestión estratégica para la toma de decisiones ejecutivas de RR.HH.

El proyecto cubrió el ciclo completo de análisis: tratamiento de datos (en Excel), modelado y creación de un **Dashboard Interactivo en Power BI**, y la elaboración de una **Presentación Ejecutiva** enfocada en los *insights*.

El análisis cruzado de datos reveló la **correlación directa** entre calidad del sueño y productividad (energía y concentración), identificando el **modelo de trabajo Presencial** como el de mayor riesgo de sobrecarga. Con base en los hallazgos, se definieron tres recomendaciones estratégicas que se centran en la **Focalización de Recursos** y la **Protección de la Desconexión**, garantizando un retorno medible sobre la inversión en iniciativas de bienestar corporativo.

---

## 1. Introducción y Tarea de Negocios 

Este proyecto es un estudio de caso práctico enfocado en la **transformación de datos de bienestar en valor estratégico** para la empresa. El objetivo es **desarrollar una estrategia de RR.HH. basada en datos** que priorice la salud y la energía del colaborador.

La dirección ha identificado que la **mitigación del riesgo de *burnout*** y la optimización de la **capacidad cognitiva** de la plantilla son cruciales para la productividad y la retención de talentos a largo plazo. El propósito es reemplazar las intervenciones de bienestar genéricas por acciones **focalizadas y con ROI mensurable**. Para ello, el proyecto se construyó siguiendo un riguroso ciclo de Business Intelligence, desde la definición de las preguntas de negocio hasta la entrega de un plan de acción estratégica.

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

---

## 4. Limpieza y Creación de Datos Analíticos 

Esta fase se centró en la preparación y el modelado de los datos dentro del entorno de Power BI para crear métricas de análisis cruciales.

### Herramientas y Metodología

| Tarea Principal | Herramienta Elegida | Justificación |
| :--- | :--- | :--- |
| **Limpieza y Transformación** | **Excel / Power BI (Query Editor)** | Tratamiento inicial de la base de datos (coherencia de tipos, gestión de nulos) y carga en el modelo de datos. |
| **Modelado y Métricas** | **Power BI (DAX)** | Creación de medidas (DAX) para calcular promedios, medianas, y *scores* agregados por segmento (departamento/modalidad), esenciales para la comparación de riesgos. |

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

---

### Comunicación (Visualizaciones del Dashboard) 

Los descubrimientos clave de la analítica se ilustran visualmente en el Dashboard Interactivo creado en Power BI.

**A continuación, se presentan algunas de las visualizaciones del Dashboard que sustentan las conclusiones:**

#### Visualización 1: Correlación entre Sueño y Capacidad Cognitiva
![Dashboard_departamento](https://github.com/RaulHamad/Big_Data_capstone/blob/main/images/dashboard_bienestar.png)
#### Visualización 2: Riesgo de Sobrecarga por Modalidad y Departamento
![Dashboard_Modalidade](https://github.com/RaulHamad/Big_Data_capstone/blob/main/images/dashboard_bienestar_4.png)

---

## 6. Recomendaciones Estratégicas

Con el objetivo de maximizar el ROI de las iniciativas de bienestar, se definieron tres prioridades accionables, basadas en los patrones de riesgo y correlación identificados:

| Prioridad | Título de la Acción | Justificación (Insight Principal) | Métrica de Éxito |
| :--- | :--- | :--- | :--- |
| **1.** | **Proteger la Desconexión** (Cultura de Límites) | El riesgo de sobrecarga es alto en el modo Presencial. La desconexión es el factor más crítico para la `Recuperación Emocional`. | Reducción del 15% en los reportes de "No" en `Ritmo de Trabajo Sostenible` en los clusters de riesgo. |
| **2.** | **Auditoría de Equidad** y Liderazgo | Las disparidades de género en métricas clave amenazan la retención y la equidad percibida. | Aumento del 10% en las puntuaciones de `Calidad del Sueño` y `Sentido del Trabajo` en los grupos identificados. |
| **3.** | **Focalización Estratégica** de Recursos | La inversión debe ser dirigida. Intervenir directamente en **Operaciones** (con foco en Propósito y Reconocimiento). | Aumento del 20% en las puntuaciones de `Ánimo` y `Concentración` en el departamento de Operaciones. |

---

## 7. Entregables del Proyecto 

| Entregable | Archivo | Descripción |
| :--- | :--- | :--- |
| **Dashboard Power BI** | **[Retos - Grupo 1v2.pbix](https://github.com/RaulHamad/Big_Data_capstone/blob/main/Retos%20-%20Grupo%201v2.pbix)** | Fichero de Power BI con el modelo de datos, cálculos DAX y visualizaciones interactivas. |
| **Presentación Ejecutiva** | **[Presentación_reto.pptx](https://github.com/RaulHamad/Big_Data_capstone/blob/main/Presentaci%C3%B3n_reto.pptx)** | Diapositivas clave con el resumen ejecutivo, *insights* y plan de acción para la dirección. |
| **Datos Ficticios** | **[dataset_respuestas_100_empleados.xlsx](https://github.com/RaulHamad/Big_Data_capstone/blob/main/dataset_respuestas_100_empleados.xlsx)** | Archivo CSV/Excel utilizado para la simulación y análisis del proyecto. |




---

# English

---

# Business Intelligence (BI) for People Management: From Data to Strategic HR Decision-Making.

This project demonstrates the application of Business Intelligence (BI) in a People Management scenario. Completed as the final challenge of a Big Data training program, the central objective was to transform a fictional dataset from a wellness survey of 100 employees into a strategic management tool for executive HR decision-making.

The project covered the complete analysis cycle: data treatment (in Excel), modeling and creation of an Interactive Dashboard in Power BI, and the development of an Executive Presentation focused on the insights.

Cross-data analysis revealed a direct correlation between sleep quality and productivity (energy and concentration), identifying the In-Office (Presential) work model as having the highest risk of overload. Based on the findings, three strategic recommendations were defined, focusing on Resource Prioritization and Protection of Disconnection, ensuring a measurable return on investment for corporate wellness initiatives.

---

## 1. Introduction and Business Task

This project is a practical case study focused on the transformation of wellness data into strategic value for the company. The goal is to develop a data-driven HR strategy that prioritizes employee health and energy.

Management has identified that mitigating the risk of burnout and optimizing the workforce's cognitive capacity are crucial for long-term productivity and talent retention. The purpose is to replace generic wellness interventions with focused actions that have a measurable ROI. To achieve this, the project was built following a rigorous Business Intelligence cycle, from defining the business questions to delivering a strategic action plan.

---

## 2. Key Business Questions 

To guide the analysis and ensure that the results were actionable, this project focused on answering the following strategic questions:

1.  **What is the main wellness factor that directly impacts the cognitive capacity (energy, concentration, and mood) of the workforce?**
2.  **What are the main risk clusters (by work modality or department) that show the greatest difficulty in maintaining a sustainable and balanced work pace?**
3.  **Is there a significant disparity in wellness and workload between genders or demographic groups that necessitates an equity audit and targeted intervention?**
4.  **Where should resources and investments in wellness initiatives be focused to guarantee the maximum Return on Investment (ROI) for the business?**

---

## 3. Data Preparation

The analysis used a fictional dataset from a wellness survey, simulating a real-world people management scenario. The data represents the responses of 100 employees to a structured questionnaire.

### Sources and Structure

* **Source:** **Fictional Data** from a Wellness Survey (100 employees) for the Big Data training final challenge.
* **Key Variables Analyzed:** he **dataset** contained 18 fields, with the most relevant being:
    * `Sleep Quality (1-10)`, `Daily Energy Level (1-5)`, `Mood (1-5)`
    * `Time to Disconnect (1-10)`, `Sustainable Work Pace (Yes/No)`, `Emotional Recovery (1-5)`
    * `Modality` (Remote, Hybrid, In-Office), `Department`, `Gender`.
* **Considerations:** The use of fictional data allowed for a complete exploration of the analysis process, from cleaning to strategic delivery.

---

## 4. Cleaning and Analytical Data Creation 

This phase focused on preparing and modeling the data within the Power BI environment to create crucial analytical metrics.

### Tools and Methodology

| Primary Task | Chosen Tool | Justification |
| :--- | :--- | :--- |
| **Cleaning and Transformation** | **Excel / Power BI (Query Editor)** | Initial treatment of the database (type coherence, null management) and loading into the data model. |
| **Modeling and Metrics** | **Power BI (DAX)** | Creation of measures (DAX) to calculate averages, medians, and aggregated scores by segment (department/modality), essential for risk comparison. |

---

## 5. Data Analysis and Insights

This section consolidates the discoveries through the exploration of the Interactive Dashboard, directly answering the business questions.

| Aggregation Performed | Analytical Focus | Analytical Objective |
| :--- | :--- | :--- |
| **Sleep Correlation** | `Sleep Quality vs. Energy / Concentration` | Measure the dependency and validate the impact of rest on productivity. |
| **Risk by Modality** | `Time to Disconnect by Modality` | Identify the risk of overload associated with specific work models (In-Office/Hybrid). |
| **Operational Risk** | `Wellness Metrics by Department` | Locate the risk clusters to focus intervention. |
| **Gender Disparities** | `Sleep Quality and Sense of Purpose at Work by Gender` | Detect equity gaps and strategic misalignments. |

### Key Discoveries (Answer to Business Questions)

The main conclusion is that wellness is a direct investment in cognitive capacity, with risks clearly localized:

* **1. The Critical Factor:** **Sleep Quality** is the strongest main driver of ´Energy´, ´Concentration´, and ´Mood´.
* **2. Overload Risk:** The **In-Office** model and employees in the **Operations** department are the groups most vulnerable to lack of disconnection and a low ´Sustainable Work Pace´.
* **3. Equity:** **Gender** disparities were identified, requiring an audit, affecting sleep quality in women and sense of purpose at work in men.

---

### Communication (Dashboard Visualizations)

The key analytical discoveries are visually illustrated in the Interactive Dashboard created in Power BI.

**Below are some of the Dashboard visualizations that support the conclusions:**

#### Visualization 1: Correlation between Sleep and Cognitive Capacity
![Dashboard_department](https://github.com/RaulHamad/Big_Data_capstone/blob/main/images/dashboard_bienestar.png)
#### Visualization 2: Overload Risk by Modality and Department
![Dashboard_Modality](https://github.com/RaulHamad/Big_Data_capstone/blob/main/images/dashboard_bienestar_4.png)

---

## 6. Strategic Recommendations

With the goal of maximizing the ROI of wellness initiatives, three actionable priorities were defined, based on the identified risk patterns and correlations:

| Priority |	Action Title |	Justification (Main Insight) |	Success Metric |
| :--- | :--- | :--- | :--- |
| **1.** | **Protect Disconnection** (Culture of Boundaries) | Overload risk is high in the In-Office mode. Disconnection is the most critical factor for ´Emotional Recovery´. | 15% reduction in "No" reports for Sustainable Work Pace within the risk clusters. |
| **2.** | **Equity Audit** and Leadership | Gender disparities in key metrics threaten retention and perceived fairness. | 0% increase in ´Sleep Quality´ and ´Sense of Purpose at Work´ scores in the identified groups. |
| **3.** | **Strategic Resource Prioritization** | Investment must be targeted. Directly intervene in **Operations** (with a focus on Purpose and Recognition). | 20% increase in ´Mood´ and ´Concentration´ scores in the Operations department. |

---

## 7. Project Deliverables 

| Deliverable | File | Description |
| :--- | :--- | :--- |
| **Dashboard Power BI** | **[Retos - Grupo 1v2.pbix](https://github.com/RaulHamad/Big_Data_capstone/blob/main/Retos%20-%20Grupo%201v2.pbix)** | Power BI file with the data model, DAX calculations, and interactive visualizations. |
| **Executive Presentation** | **[Presentación_reto.pptx](https://github.com/RaulHamad/Big_Data_capstone/blob/main/Presentaci%C3%B3n_reto.pptx)** | Key slides with the executive summary, insights, and action plan for management. |
| **Fictional Data** | **[dataset_respuestas_100_empleados.xlsx](https://github.com/RaulHamad/Big_Data_capstone/blob/main/dataset_respuestas_100_empleados.xlsx)** | CSV/Excel file used for the project simulation and analysis. |

---


