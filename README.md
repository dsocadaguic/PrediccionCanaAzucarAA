<img src="https://github.com/dsocadaguic/PrediccionCanaAzucarAA/blob/main/img/EscudoUN.png" width="400"/>

# Tesis: Predicción espacial del rendimiento del cultivo de caña de azúcar mediante aprendizaje de máquina

***Autor:*** Diego Arley Socadagui Casas @[dsocadaguic](https://github.com/dsocadaguic).

***Director:*** Prof. Ph.D(s). Andrés Felipe Rodriguez Vasquez ([perfil](https://scholar.google.es/citations?user=7D4jWaUAAAAJ&hl=es))

***Codirectora:*** Prof. Ph.D. Yolanda Rubiano Sanabria ([perfil](https://cienciasagrarias.bogota.unal.edu.co/facultad/profesores/yolanda-rubiano-sanabria))

## Descripción
El cultivo de caña de azúcar es fundamental para la economía agrícola de Colombia, particularmente en el Valle del Río Cauca, una región que se enfrenta a desafíos como el cambio climático y la gestión eficiente de recursos. En este contexto, el uso de tecnologías de aprendizaje de máquina (AA) y datos geoespaciales se presenta como una solución innovadora para predecir de manera precisa el rendimiento de los cultivos, optimizando el uso de agua y otros insumos clave. Este estudio propone una metodología que integra datos históricos de clima, suelo y manejo agrícola con algoritmos de AA como Random Forest, XGBoost, y Catboost, con el fin de desarrollar modelos predictivos robustos que proporcionen estimaciones espaciales del rendimiento de la caña de azúcar. Los resultados muestran que los modelos basados en AA superan a los métodos tradicionales (cómo regresiones lineales y penalizadas), proporcionando predicciones más precisas que pueden ser implementadas para la planificación agrícola y la gestión de recursos en el Valle del Río Cauca, más específicamente en el municipio de La Candelaria. La investigación destaca el potencial de las técnicas avanzadas de AA para mejorar la eficiencia productiva y contribuir a una agricultura más sostenible.

## Link
El documento puede consultarse en el siguiente enlace [Thesis Project]().

## Explicación del directorio

```
Proyecto de Tesis
├── code: Contains the Jupyter notebooks used
│   ├── 00_PreparingData.ipynb
│   ├── 01_EDA.ipynb
│   └── 02_ExtractJurisprudence.ipynb
│   ├── 03_PreprocessingText.ipynb
│   └── 04_Citation_standard.ipynb
├── data: Contains the datasets downloaded to develop the project
│   ├── ...
│   ├── ...
│   ├── ...
│   ├── ...
│   ├── ...
│   └── ...
├── img: Contains the KU Leuven logo
├── models: Contains the models created to do the ontological search
│   ├── ...
│   ├── ...
│   ├── ...
│   ├── ...
│   └── ...
└── output: Contains the processed data, and the results obtained from the NLP analysis 
└── requirements.txt: Contains all the packages used in the project

```

## Instrucciones para ejecutar el código de este repositorio

1. Install [MongoDB](https://www.mongodb.com/docs/manual/installation/).
2. Clone the repository.
```
git clone -b main https://github.com/amgiraldov/thesisKULeuven.git
```
3. Create a new virtual environment with Python 3.8.15 version.
```
pyenv virtualenv 3.8.15 <name>
```
4. Activate the environment.
```
pyenv activate <name>
```
5. Install the `requirements.txt` file into the virtual environment.
```
pip install -r requirements.txt
```
