# Proyecto de Teledetección con Random Forest

Este proyecto utiliza el algoritmo Random Forest para clasificar imágenes de satélite Landsat 9 y predecir los tipos de suelo entre: cuerpo de agua, zona urbana y vegetación,
tanto en Buenos Aires (Argentina) como en Australia. 
Se utiliza Google Earth Engine para acceder y procesar las imágenes satelitales.

## Librerías Utilizadas

El proyecto hace uso de las siguientes librerías de Python:

- **geemap**: Interfaz Python para Google Earth Engine, facilitando la visualización y análisis de datos geoespaciales.
- **ee**: Biblioteca Earth Engine para acceder y analizar datos satelitales y geoespaciales.
- **pandas**: Para la manipulación y análisis de datos estructurados.
- **matplotlib.pyplot**: Para la visualización de datos mediante gráficos.
- **google.colab**: Utilizado para la integración de Google Colab con Google Drive.
- **IPython.display, ipywidgets**: Para mostrar imágenes y widgets interactivos en Jupyter notebooks.
- **folium**: Para crear mapas interactivos en HTML.
- **json, requests**: Para el manejo de datos en formato JSON y realizar solicitudes HTTP.

Además, se utiliza:

- **scikit-learn**:
  - **RandomForestClassifier**: Para entrenar y predecir con el modelo Random Forest.
  - **StandardScaler**: Para estandarizar las características antes de entrenar el modelo.
  - **train_test_split**: Para dividir los datos en conjuntos de entrenamiento y prueba.
  - **GridSearchCV**: Para la búsqueda de hiperparámetros mediante validación cruzada.
  - **make_pipeline**: Para construir tuberías de procesamiento de datos.
  - **accuracy_score, classification_report, confusion_matrix, ConfusionMatrixDisplay**

![Landsat Timeline](https://appliedsciences.nasa.gov/sites/default/files/landsat-timeline.jpg)
