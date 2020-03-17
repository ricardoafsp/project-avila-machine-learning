# project-avila-machine-learning

### El proyecto consiste en lograr la mejor predicción de autores de la biblia "ficción", los cuales obtenemos la información por medio de un dataset. El dataset lo trabajamos como dataframe que contiene toda la información posible de los mismos. Luego utilizar distintos modelos de machine learning y con ello lograr la mejor predicción posible de sus respectivos precios.

### Estructura del trabajo realizado:
* Limpieza y análisis del dataframe.
* Utilizar varios modelos para predecir el autor.
* Modelos utilizados y su respectivo resultado:
HistGradientBoostingClassifier (learning rate 0.25)
HistGradientBoostingClassifier
RandomForestClassifier (n_estimators = 300)
GradientBoostingClassifier
KNeighborsClassifier
LinearSVC

### Conclusión: Observamos que el modelo que mejor resultado da es el HistGradientBoostingClassifier, y como por defecto su Learning Rate es de 0.10 lo aumentamos a un 0.25 para mejorar el resultado obtenido.