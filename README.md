# Diamonds Project

En este proyecto se predice mediante modelos de  aprendizaje automatico supervisado el precio de los diamantes.

<p align="center">
  <img width="400" height="300" src="https://user-images.githubusercontent.com/66179117/95110536-76f3fb80-073e-11eb-9395-6f955024cfae.png">
</p>

#### **Detalles a tener en cuenta**:
 El precio de los diamantes depende, entre otras cosas, de la talla(cut), la claridad(clarity), el color(color) y el peso(carat).


## ¿Qúe encontramos en cada archivo?

En el archivo diamonds train encontraremos la limpieza del dataset de *"train.csv"* utilizado y el entrenamiento de cada uno de los modelos para conocer cuál se adapta mejor a la realidad.
Para entrenarlo utilizamos el test split con un 80% para entrenamiento y un 20% para el test
Los modelos utilizados son:
- RandomForest
- GradientBoost
- HistGradientBoost
- KNeighbors
- DecisionTree
- ExtraTrees
----------
En la carpeta de test, hemos entrenado los modelos con mejores resultados  en el dataset completo de *"train.csv", y hemos completado con nuestras predicciones de precios del diamante el dataset *"predict.csv"

<p align="center">
<img width="523" alt="Captura de pantalla 2020-10-05 a las 22 38 52" src="https://user-images.githubusercontent.com/66179117/95129757-c1d03c00-075b-11eb-9de3-d6e46790a855.png">
</p>


--------


Las **librerías** que se han utilizado para realizar este modelo son:
- numpy
- pandas
- matplotlib
- sklearn
