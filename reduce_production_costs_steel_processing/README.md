# Оптимизация производственных расходов металлургического комбината

## Описание проекта

Чтобы уменьшить потребление электроэнергии на этапе обработки стали необходимо построить модель, которая предскажет температуру стали.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **matplotlib**
- **time**
- scipy.**stats**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**StratifiedKFold**
- sklearn.metrics.**mean_absolute_error**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_model.**Lasso**
- sklearn.linear_model.**Ridge**
- pyod.models.knn.**KNN**
- sklearn.preprocessing.**StandardScaler**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- xgboost.**XGBRegressor**
- functools.**partial**

## 

## Общий вывод

- Загружены данные и проведена предобработка.
- Выполнено сравнение моделей с использованием различных наборов гиперпараметров.
- Выбрана лучшая модель по результатам метрики MAE.
- Для общей оценки по трем параметрам был создан относительный рейтинг.
