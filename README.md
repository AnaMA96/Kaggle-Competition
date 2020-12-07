# 💎💎 **DIAMONDS** 💎💎

Este proyecto ha consistido en participar en una competición en [Kaggle](https://www.kaggle.com/c/diamonds-datamad1020-rev/overview) para la cual hemos tratado de predecir el precio de los diamantes a partir de los datasets proporcionados en la misma.

![Alt](https://github.com/AnaMA96/Kaggle-Competition/blob/main/output/images/The%20Diamond%20Kaggle%20Competition.jpg)

El modelo que me ha permitido ocupar la siguiente posición en la competición ha sido generado con [Automatic Learning de H2O](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html):

````
automl = H2OAutoML(max_models=50, seed=1,max_runtime_secs=1800, sort_metric='MSE')
automl.train(x, y, training_frame=h2train)
````





![Alt](https://github.com/AnaMA96/Kaggle-Competition/blob/main/output/images/Captura%20de%20pantalla%202020-12-07%20a%20las%202.17.54.png)



