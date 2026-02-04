# 👥 Project Talent Flow – People Analytics con Python
## 📌 Descripción General
Project Talent Flow es un proyecto de People Analytics enfocado en la realización de un Análisis Exploratorio de Datos (EDA) profundo para identificar los factores clave que influyen en la rotación laboral (Attrition).
A partir de un dataset de 1,470 empleados y 35 variables, se analizan aspectos demográficos, laborales, salariales y de satisfacción con el fin de apoyar la toma de decisiones estratégicas en Recursos Humanos.

## 🎯 Objetivos
- Analizar datos de empleados para identificar los principales impulsores de la rotación
- Detectar perfiles con mayor riesgo de abandono
- Generar insights accionables para estrategias de retención de talento
- Establecer una base analítica para futuros modelos predictivos

## 📊 Dataset
- Registros: 1,470 empleados
- Variables: 35 columnas
- Tipos de datos: Demográficos, laborales, salariales, satisfacción y desempeño

## 🔍 Etapas del Análisis
1. Calidad y Preparación de Datos
- Revisión de estructura y tipos de datos
- Eliminación de columnas irrelevantes (por ejemplo, índices exportados)
- Evaluación y tratamiento de valores nulos
- Verificación de registros duplicados
2. Análisis Exploratorio de Datos (EDA)
- Resumen estadístico de variables numéricas
- Análisis de distribuciones (edad, ingresos, antigüedad, distancia al trabajo)
- Identificación de valores atípicos con enfoque interpretativo de negocio
3. Análisis de Rotación (Attrition)
- Comparación entre empleados que permanecen y los que renuncian
- Evaluación de la rotación según:
  - Edad y antigüedad
  - Nivel de ingresos
  - Horas extra (OverTime)
  - Cargo y departamento
  - Frecuencia de viajes y distancia al trabajo
4. Análisis Multivariado
- Identificación de perfiles de alto riesgo combinando:
  - Bajos ingresos + horas extra
  - Baja antigüedad + menor edad
  - Confirmación de que el salario y la carga laboral influyen más en la rotación que los factores ambientales aislados

## 💡 Principales Hallazgos
- La rotación es más alta durante los primeros 0–2 años en la empresa
- Los rangos salariales bajos concentran la mayor tasa de renuncia
- Los empleados que realizan horas extra presentan mayor probabilidad de salida
- El departamento de Sales muestra la mayor rotación relativa
- La juventud y una mayor distancia al lugar de trabajo incrementan el riesgo de abandono

## 🛠️ Herramientas y Tecnologías
- Lenguaje: Python
- Librerías: Pandas, NumPy, Matplotlib, Seaborn
- Entorno: Jupyter Notebook

## 📈 Valor para el Negocio
- Este proyecto permite a las áreas de Recursos Humanos:
  - Diseñar estrategias de compensación más efectivas
  - Fortalecer procesos de inducción y retención temprana
  - Identificar señales tempranas de rotación
  - Tomar decisiones basadas en datos para la gestión del talento
