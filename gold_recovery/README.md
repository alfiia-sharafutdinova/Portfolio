# Восстановление золота

[html on GitHub](https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/gold_recovery/gold_recovery.html)  
[ipynb on GitHub](https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/gold_recovery/gold_recovery.ipynb)

[html on htmlpreview](https://htmlpreview.github.io/?https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/gold_recovery/gold_recovery.html)  
[ipynb on nbviewer](https://nbviewer.org/github/alfiia-sharafutdinova/Portfolio/blob/main/gold_recovery/gold_recovery.ipynb)

## Описание

Необходимо подготовить модель для предсказания коэффицента восстановления золота из золосодержащей руды. Модель поможет оптимизировать производство. В распоряжении данные с параметрами добычи и очистки.

## Навыки и инструменты

* **pandas**
* **seaborn**
* **matplotlib**
* sklearn.linear_models.**LinearRegression**
* sklearn.ensemble.**RandomForestRegressor**
* sklearn.preprocessing.**StandardScaler**
* sklearn.model_selection.**cross_val_score**, **GridSearchCV**, **RandomizedSearchCV**
* sklearn.metrics.**mean_absolute_error**, **make_scorer**
* pandas_profiling.**ProfileReport**

## Общий вывод

Была проведена кросс-валидация различных моделей. Для решения поставленной задачи обучена модель случайного леса. Проверка модели на адекватность подтвердила эффективность предсказаний.
