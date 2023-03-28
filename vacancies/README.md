# Вакансии

[html](https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/vacancies/vacancies.html) [ipynb](https://github.com/alfiia-sharafutdinova/Portfolio/blob/main/vacancies/vacancies.ipynb)

## Описание

Необходимо обучить модель для предсказания зарплаты соискателя по описанию вакансии. В распоряжении данные о вакансиях с [Kaggle](https://www.kaggle.com/competitions/hse-2nd-step-in-nlp-bootcamp/leaderboard).

## Навыки и инструменты

* **pandas**
* **matplotlib**
* **seaborn**
* **phik**
* sklearn.feature_extraction.text.**TfidfVectorizer**, **CountVectorizer**
* sklearn.preprocessing.**OrdinalEncoder**, **OneHotEncoder**
* sklearn.compose.**ColumnTransformer**
* sklearn.pipeline.**Pipeline**, **make_pipeline**
* sklearn.model_selection.**cross_val_score**
* **optuna**
* **nltk**
* pymorphy2.**MorphAnalyzer**
* gensim.models.**Word2Vec**
* catboost.**CatBoostRegressor**

## Общий вывод

Предобработка описаний вакансий была проведена с использованием Word2Vec с усреднением эмбеддингов слов с весами TF-IDF. Была обучена модель градиентного бустинга CatBoost, предсказывающая зарплату по описанию вакансии. 
