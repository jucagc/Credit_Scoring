# Análisis de Riesgo Crediticio 📊

![imagine3](https://github.com/user-attachments/assets/4537d7b3-e1c1-473c-bc6f-a733594bed1d)


---

## Presentado por: Data & ML Innovators
- **Alejandra Cruz R.**
- **Brusl y Patiño S.**
- **Juan García C.**

**Marzo 2025**  
**Bootcamp Xperience**

---

## Descripción del Proyecto 🚀

Este proyecto tiene como objetivo **predecir el riesgo crediticio** de los clientes utilizando técnicas de **machine learning**. El enfoque principal es identificar la probabilidad de incumplimiento crediticio (default) en función de las características financieras y personales de los clientes, con el fin de tomar decisiones más precisas y reducir los riesgos asociados.

---

## El Desafío del Riesgo Crediticio 🎯

### Entorno Competitivo
- Decisiones precisas en un mercado regulado.
- La **confianza y estabilidad** son una prioridad estratégica clave.
- La **gestión del riesgo** es fundamental para predecir y mitigar posibles incumplimientos.

### Identificación de Clientes Aptos
- **Enfoque preciso**: Identificar clientes aptos para otorgar créditos.
- **Disminuir riesgos**: Evaluar la solvencia de los clientes.
- **Herramientas confiables**: Utilizar modelos predictivos para mejorar la toma de decisiones.

---

## Preguntas Clave del Negocio ❓

1. ¿Cuál es la probabilidad de incumplimiento crediticio de un cliente en función de sus características financieras y personales?
2. ¿Qué variables tienen el mayor impacto en la predicción del riesgo crediticio?
3. ¿Cómo se puede mejorar la precisión del modelo de predicción de riesgo crediticio utilizando técnicas de machine learning?

---

## Etapas del Proyecto 🛠️

### 1. Preprocesamiento de Datos 🔧
- **Identificación de datos anómalos**: Limpieza de datos y manejo de valores atípicos.
- **Descriptivos numéricos y categóricos**: Análisis de variables como `Income`, `Assets`, `Debt`, etc.
- **Truncamiento de valores atípicos**: Ajuste de datos para mejorar la calidad del análisis.
- **Agrupamiento de categorías**: Simplificación de variables cualitativas.

### 2. Exploración de Datos 🔍
- **Datos Numéricos**:
  - Histogramas de distribución.
  - Gráficos de distribución acumulada (CDF).
- **Datos Cualitativos**:
  - Análisis de categorías como `home`, `marital`, `records`, y `job`.
  - Observaciones clave:
    - Mayor riesgo en categorías como `other`, `private`, `rent` (home).
    - Mayor riesgo en `single` y `other` (marital).
    - Mayor riesgo en `yes` (records).
    - Mayor riesgo en `unk`, `part time`, y `other job` (job).

### 3. Construcción de Modelos 🎨
- **Partición de datos**: División en conjuntos de entrenamiento (`X_train`, `y_train`) y prueba (`X_test`, `y_test`).
- **Modelos de Clasificación**:
  - **Modelo Logit**.
  - **Modelo Árbol de Decisión (Tree)**.
  - **Modelo Random Forest**.

### 4. Evaluación y Selección de Modelos 🏋‍♂️
- **Modelo Logit**: AUC-ROC de **0.7693**.
- **Modelo Árbol de Decisión**: AUC-ROC de **0.7842**.
- **Modelo Random Forest**: AUC-ROC de **0.8424** (el más preciso).

---

## Conclusiones 📝

1. **Random Forest** fue el modelo más preciso en esta base de datos.
2. **Solicitud previa**: Es importante evaluar las solicitudes de crédito con un enfoque práctico y basado en datos.
3. **Próximos pasos**:
   - **XGBoost**: Replicar el análisis utilizando el modelo XGBoost.
   - **Otras métricas**: Considerar métricas adicionales para mejorar la evaluación.
   - **Balancear datos**: Mejorar las métricas mediante el balanceo de la base de datos.

---

## Tecnologías Utilizadas 💻

- **Lenguaje de Programación**: Python.
- **Librerías**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- **Herramientas**: Jupyter Notebook, Git.

---

## Instalación y Uso 🚀

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/pones-tu-usuarrio/analisis-riesgo-crediticio.git
