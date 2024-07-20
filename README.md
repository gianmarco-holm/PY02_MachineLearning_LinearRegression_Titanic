# Modelo de Regresión Lineal de sobrevivientes de Titanic

## Descripción del Proyecto

Este proyecto utiliza técnicas de machine learning, específicamente un modelo de regresión lineal para poder predecir si una persona puede sobrevivir o no al titanic

## Contenido

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Contenido](#contenido)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados](#resultados)
- [Conclusión](#conclusión)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Requisitos

- Python 3.x
- Librerías:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - plotly
  - scikit-learn
  - regressors
  - pickle

## Instalación

1. Puedes descargar el archivo y correrlo en Google Colab

## Uso
Carga los datos:

```python
# El archivo lo dejare tambien en el repositorio
import pandas as pd

# Extraer datos
df = pd.read_csv('./drive/MyDrive/machine_learning/data/titanic.csv')
df.head()
```

## Resultados
Los resultados del modelo se presentan mediante gráficos de dispersión, matrices de correlación y gráficos de residuos para visualizar la precisión y las predicciones del modelo.

## Conclusión
El modelo inicial tiene un coeficiente de determinación (R²) de aproximadamente 0.50, lo cual es aceptable para la predicción de gastos hospitalarios. Se recomienda seguir afinando el modelo inicial y probar con diferentes características y técnicas para mejorar la precisión.

## Contribuciones
Las contribuciones son bienvenidas. Para grandes cambios, por favor abre un issue primero para discutir lo que te gustaría cambiar.
