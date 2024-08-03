# TelcoChurn Insights

Este proyecto se centra en la aplicación y el estudio de métodos de interpretación modelo-agnósticos, con un enfoque específico en SHAP (SHapley Additive exPlanations), para analizar y explicar las predicciones de churn de clientes en el sector de telecomunicaciones. Utilizando el dataset "Telco Customer Churn" disponible en Kaggle, el proyecto implementará modelos de predicción de churn, como árboles de decisión y Random Forest, y aplicará SHAP para desentrañar la influencia de diversas características en las predicciones del modelo.

## Estructura del Jupyter Notebook

1. **Setup**

   - Importación de las librerías necesarias.
   - Configuración inicial requerida para el análisis.

2. **Exploratory Data Analysis (EDA)**

   - **Descripción de las Columnas**: Explorar cada característica del dataset.
   - **Verificación de Datos Faltantes**: Identificar y manejar posibles valores faltantes.
   - **Análisis Gráfico de Datos**: Realizar visualizaciones para comprender las distribuciones y relaciones.
   - **Conclusiones del EDA**: Resumir los insights y preparar el camino para el modelado.

3. **Modelos de Predicción**

   - **Árbol de Decisión**: Implementar y evaluar un modelo de árbol de decisión.
   - **Random Forest**: Implementar y evaluar un modelo de Random Forest.
   - **Análisis SHAP**:
     - **Cálculo de Valores SHAP**: Generar valores SHAP para el modelo de Random Forest.
     - **SHAP Summary Plot**: Visualizar la importancia global de las características.
     - **SHAP Dependence Plots**: Analizar cómo ciertas características impactan en la predicción del modelo.
     - **SHAP Force Plots**: Mostrar la contribución de las características a predicciones individuales.
   - [aquí se explicará el análisis SHAP y las visualizaciones]

4. **Conclusión**
   - Recapitulación de los hallazgos del análisis.
   - Discusión sobre la aplicabilidad de los resultados en estrategias de retención de clientes.

## Dataset

El dataset utilizado para este análisis es el "Telco Customer Churn" disponible en Kaggle. Puedes acceder y descargar el dataset directamente desde este enlace: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data).

## Instrucciones para Ejecutar el Jupyter Notebook

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tuusuario/TelcoChurnInsights.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd TelcoChurnInsights
   ```

3. Instala las dependencias necesarias:

   ```bash
   pip install -r requirements.txt
   ```

4. Ejecuta Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Abre el archivo `TelcoChurnInsights.ipynb` y sigue las instrucciones en cada celda para replicar el análisis.

## Requerimientos

- Python 3.7 o superior
- Jupyter Notebook
- Librerías especificadas en `requirements.txt` (por definir)

## Autor

Oscar Estrada Morales
Sara María Paguaga
Guillermo Santos Barrios
José Cayetano Molina

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.
