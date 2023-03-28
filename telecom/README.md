# Телеком

[html](https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/telecom/telecom.html) [ipynb](https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/telecom/telecom.ipynb)

## Описание

Необходимо обучить модель для прогнозирования оттока клиентов телекоммуникационной компании. В распоряжении данные о контрактах клиентов.

## Навыки и инструменты

* **pandas**
* **matplotlib**
* **seaborn**
* **phik**
* sklearn.linear_model.**LogisticRegression**
* sklearn.ensemble.**RandomForestClassifier**
* catboost.**CatBoostClassifier**
* sklearn.preprocessing.**OneHotEncoder**, **OrdinalEncoder**, **StandardScaler**
* sklearn.compose.**ColumnTransformer**
* sklearn.pipeline.**Pipeline**
* from sklearn.model_selection.**train_test_split**, **cross_val_score**, **GridSearchCV**
* sklearn.metrics.**accuracy_score**, **roc_auc_score**
* **shap**

## Общий вывод

Была проведена кросс-валидация различных моделей. Для решения задачи была обучена модель градиентного бустинга CatBoost, с помощью которой можно прогнозировать вероятность ухода клиента оператора связи.
