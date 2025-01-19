# ML_PS2_Falcone_Morales_Riverti  
**Problem Set 2 - Machine Learning - Falcone, Morales y Riverti**

---

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir la condición de pobreza de los hogares utilizando técnicas de aprendizaje automático. Se procesan y analizan datos relacionados con características de los hogares y las personas, para construir modelos predictivos que clasifiquen los hogares como pobres o no pobres. A lo largo del proyecto, se utilizan diversas metodologías para el análisis de datos, modelado y evaluación del desempeño de los modelos.

El codigo esta inspirado en el concurso del Banco Mundial: https://www.drivendata.org/competitions/50/worldbank-poverty-prediction/page/97/

El sitio web del concurso es: https://www.kaggle.com/competitions/mlunlp-2024-ps-2

---

## Principales Etapas del Proyecto

1. **Procesamiento de Datos**  
   - Limpieza de datos: tratamiento de valores extremos, imputación de valores faltantes y transformación de variables.  
   - Generación de nuevas variables: creación de indicadores como promedio de educación, hacinamiento y porcentaje de ocupados.  

2. **Análisis Descriptivo**  
   - Visualización de datos para explorar y entender la distribución de variables clave.  
   - Cálculo de estadísticas descriptivas como promedios, modas y varianzas.  

3. **Modelado Predictivo**  
   - Construcción de modelos utilizando técnicas de regresión logística, boosting (AdaBoost) y Random Forest.  
   - Evaluación de los modelos mediante métricas como precisión, AUC-ROC y matriz de confusión.  

4. **Validación y Ajuste de Modelos**  
   - Selección de los mejores hiperparámetros para maximizar el desempeño predictivo.  
   - Aplicación de los modelos al conjunto de prueba para generar predicciones finales.  

5. **Exportación de Resultados**  
   - Las predicciones se exportan en formato CSV para análisis posterior y validación.

---

## document

Esta carpeta contiene:
  - ddi-documentation-spanish-608.pdf como documento metodologico de las encuestas
  - Etiquetas.xlsx : contiene las variables utilizadas y su explicacion
  - tipo_var.xlsx : contiene la clasificacion de variables por continua o dummy
  - classification_boosting_1, classification_boosting_2, etc. contienen las predicciones

## Instrucciones para el Repositorio

### Clonar el Repositorio
Abrir cmd

cd C:... (completar con directorio local)

git clone https://github.com/santiagoriverti/ML_PS2_Falcone_Morales_Riverti.git

### Actualizar repositorio local
Abrir cmd 

cd C:... (completar con direccion del repositorio local)

git pull

### Actualizar repositorio remoto en rama principal
Abrir cmd

cd C:... (completar con direccion del repositorio local)

git status

git add .

git commit -m "comentario"

git push origin main

### Otras aclaraciones

El codigo fue diseñado en Google Colab. Para reproducirlo completamente debe cargar en el entorno del mismo los siguientes archivos:

1. train_personas.csv
2. test_personas.csv
3. train_hogares.csv
4. test_hogares.csv
5. tipo_var.xlsx

Del 1 al 4 se encuentran el el sitio de Kaggle. El numero 5 esta disponible en la carpeta "document" de este repositorio
