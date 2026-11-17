# Proyecto Integrador: Analítica de Empleados

**Materia:** Programación Avanzada  
**Grupo:** GAB-2402  
**Docente:** Prof. Fabián Soberanes Martín

## 1. Descripción del proyecto

El proyecto consiste en desarrollar un sistema de análisis de datos de empleados utilizando Python. Se busca estudiar información relacionada con edad, experiencia laboral, departamento, ciudad, satisfacción, antigüedad y salario.

El sistema permite identificar patrones, comparar salarios y realizar predicciones mediante modelos de aprendizaje automático.

## 2. Objetivo

Desarrollar una solución que permita procesar, analizar y visualizar información de empleados, integrando técnicas estadísticas, Machine Learning y una aplicación web interactiva.

## 3. Tecnologías utilizadas

- Python
- Pandas y NumPy
- Matplotlib y Seaborn
- Plotly
- SciPy
- Scikit-learn
- SQLite
- Joblib
- Streamlit

## 4. Desarrollo del proyecto

### 4.1 Limpieza de datos

Se eliminaron registros duplicados, se trataron valores faltantes y se revisaron valores extremos. También se generaron variables adicionales para facilitar el análisis.

### 4.2 Visualización de datos

Se elaboraron gráficas para analizar la distribución de salarios, comparar departamentos y estudiar relaciones entre variables.

### 4.3 Análisis estadístico

Se realizaron pruebas estadísticas para comparar los salarios de distintos grupos de empleados.

### 4.4 Machine Learning

Se implementaron modelos de regresión para estimar salarios y modelos de clasificación para identificar empleados con salarios altos.

### 4.5 Base de datos

Se utilizó SQLite para almacenar información y realizar consultas sobre los empleados.

### 4.6 Aplicación Streamlit

Se desarrolló un dashboard interactivo que incluye:

- Filtros por departamento y ciudad.
- Indicadores KPI.
- Gráficas de distribución y comparación salarial.
- Análisis de experiencia y salario.
- Formulario para predecir salarios.

## 5. Resultados

Se obtuvo una aplicación que integra análisis de datos, visualización y predicción salarial.

**Métricas del modelo:**

- MAE: Pendiente de agregar.
- R²: Pendiente de agregar.
- Accuracy: Pendiente de agregar.

## 6. Limitaciones

- Los resultados dependen de la calidad de los datos.
- Las predicciones son estimaciones y no representan salarios garantizados.
- Los modelos están condicionados por las variables disponibles y los datos utilizados durante el entrenamiento.

## 7. Conclusión

El proyecto permitió integrar conocimientos de programación, análisis de datos, estadística y aprendizaje automático.

Se desarrolló una aplicación interactiva que facilita la consulta de información de empleados, la comparación de salarios y la estimación de ingresos mediante modelos predictivos.

## 8. Ejecución

Para iniciar la aplicación, abre Anaconda Prompt, ubícate en la carpeta donde se encuentra `app.py` y ejecuta:

```bash
streamlit run app.py
```

La aplicación estará disponible en:

http://localhost:8501