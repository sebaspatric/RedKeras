# Predicción de Diabetes utilizando Redes Neuronales

En este proyecto, desarrollaremos un modelo predictivo utilizando redes neuronales para predecir si un paciente tiene diabetes o no. Utilizaremos el conjunto de datos de diabetes, que contiene varias características médicas de los pacientes, como el número de embarazos, la concentración de glucosa en plasma, la presión arterial, el grosor del pliegue cutáneo, la insulina, el índice de masa corporal (IMC), la función de pedigrí de diabetes y la edad.

## Objetivo

El objetivo principal de este proyecto es desarrollar un modelo predictivo utilizando redes neuronales que pueda predecir con precisión si un paciente tiene diabetes o no, basándose en las características médicas proporcionadas en el conjunto de datos.

## Conjunto de Datos

El conjunto de datos de diabetes contiene las siguientes características:

- **Pregnancies**: Número de veces embarazada.
- **Glucose**: Concentración de glucosa en plasma.
- **BloodPressure**: Presión arterial diastólica.
- **SkinThickness**: Grosor del pliegue cutáneo del tríceps.
- **Insulin**: Insulina en suero de 2 horas.
- **BMI**: Índice de masa corporal (IMC).
- **DiabetesPedigreeFunction**: Función de pedigrí de diabetes.
- **Age**: Edad del paciente.
- **Outcome**: Variable de destino que indica si el paciente tiene diabetes (1) o no (0).

## Pasos del Proyecto

El proyecto seguirá los siguientes pasos:

1. **Carga y Preprocesamiento de Datos**: Cargar el conjunto de datos de diabetes, realizar cualquier preprocesamiento necesario, como manejo de valores faltantes y normalización de características.

2. **División de los Datos**: Dividir los datos en conjuntos de entrenamiento y prueba para entrenar y evaluar el modelo, respectivamente.

3. **Definición del Modelo de Red Neuronal**: Definir la arquitectura del modelo de red neuronal utilizando capas proporcionadas por Keras.

4. **Compilación del Modelo**: Compilar el modelo especificando la función de pérdida, el optimizador y las métricas de evaluación.

5. **Entrenamiento del Modelo**: Entrenar el modelo utilizando los datos de entrenamiento.

6. **Evaluación del Modelo**: Evaluar el rendimiento del modelo utilizando los datos de prueba.

7. **Hacer Predicciones y Conclusiones**: Hacer predicciones utilizando el modelo entrenado y sacar conclusiones basadas en los resultados obtenidos.

## Tecnologías Utilizadas

- Python
- Biblioteca Keras (para el desarrollo del modelo de red neuronal)
- Biblioteca pandas (para manipulación de datos)
- Biblioteca scikit-learn (para división de datos y métricas de evaluación)

## Archivos

- `diabetes.csv`: Archivo CSV que contiene el conjunto de datos de diabetes.
- `diabetes_prediction.ipynb`: Archivo Jupyter Notebook que contiene el código Python para el desarrollo del modelo predictivo.

## Instrucciones de Ejecución

1. Instalar las bibliotecas necesarias: `pip install pandas scikit-learn keras`.

2. Clonar o descargar este repositorio en tu máquina local.

3. Abrir el archivo `diabetes_prediction.ipynb` utilizando Jupyter Notebook o cualquier otro entorno de desarrollo de Python.

4. Ejecutar cada celda de código en el orden especificado para cargar, preprocesar, entrenar y evaluar el modelo.

## Resultados y Conclusiones

Los resultados obtenidos del modelo se evaluarán en términos de precisión y se sacarán conclusiones basadas en su rendimiento en la predicción de la diabetes en pacientes.

¡Gracias por revisar este proyecto! Si tienes alguna pregunta o comentario, no dudes en contactarnos.