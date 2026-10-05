# Modelo de Riesgo Crediticio, Originación y Cobranza (CNBV)

## Resumen del Proyecto
Proyecto académico desarrollado en equipo para la materia de Administración Integral de Riesgo (BUAP). 
El objetivo del proyecto fue evaluar el riesgo de crédito mediante modelos de originación, cobranza y la constitución de reservas bajo la normativa de la CNBV (Anexos 21 y 22).

## Mi Contribución Específica
- **Mapeo y Homologación Sectorial:** Desarrollo en Python de algoritmos para la reclasificación y homologación de claves SCIAN hacia los sectores regulados por la CNBV.
- **Cálculo de Reservas Preventivas (CNBV):**
  - Implementación paramétrica del **Anexo 21** para la evaluación de la Cartera Comercial (MIPYMES).
  - Implementación del **Anexo 22** para la evaluación de Grandes Corporativos (combinación de factores cuantitativos y cualitativos).
  - Estimación de la Probabilidad de Incumplimiento (PI) mediante funciones logísticas de calibración, Severidad de la Pérdida (SP) y Exposición al Incumplimiento (EAD) para el cálculo de la Pérdida Esperada.
  $$\text{PE} = \text{PI} \times \text{SP} \times \text{EAD}$$
  
## Tecnologías y Librerías Utilizadas

El desarrollo de este proyecto se fundamenta en las siguientes herramientas de análisis de datos y modelado predictivo:

* **Lenguaje:** Python
* **Manipulación y Análisis de Datos:** `pandas`, `numpy`, `openpyxl`
* **Modelado Crediticio & Binning:** `optbinning`, `scorecardpy`
* **Machine Learning & Validación:** `scikit-learn` (Regresión Logística, Random Forest, Métricas ROC/AUC, K-Fold Cross Validation), `imbalanced-learn` (SMOTE, UnderSampling)
* **Visualización Interactiva & Gráfica:** `plotly`, `matplotlib`, `seaborn`
* **Formateo Matemático:** `IPython.display` (Markdown, Math LaTeX)

## Créditos
Este proyecto fue realizado de manera colaborativa por:

- **Gustavo Rojas López**
- **Alexis Gimar Isidro Meza**
- **Ulises Galicia Flores**
- **Roberto López Cancino**
- **Milton Escobar Trujillo**
