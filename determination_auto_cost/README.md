# Определения стоимости автомобилей

## Описание проекта

На основе исторические данные необходимо построить модель для определения стоимости автомобиля.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **matplotlib**
- **time**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**StratifiedKFold**
- sklearn.metrics.**mean_squared_error**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_model.**Lasso**
- sklearn.linear_model.**Ridge**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- functools.**partial**

## 

## Общий вывод

- Загружены данные и проведена предобработка.
- Выполнено сравнение моделей с использованием различных наборов гиперпараметров.
- Выбрана лучшая модель по результатам метрики RMSE и времени обучения.
- Для общей оценки по трем параметрам был создан относительный рейтинг.
