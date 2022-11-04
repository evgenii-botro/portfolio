# Прогноз количества заказов для сервиса такси

## Описание проекта

Требуется спрогнозировать количество заказов такси в аэропорту на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.


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
- sklearn.metrics.**mean_squared_error**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_model.**Lasso**
- sklearn.linear_model.**Ridge**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**StandardScaler**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- statsmodels.tsa.seasonal.**adfuller**
- functools.**partial**

## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. 
Во время проекта были изучены способы предсказания веременных рядов С помощью 7ми регрессоров и константной модели.
Также добавили в список CatBoostRegressor без указания параметров. Регрессор самостоятельно ищет лучшие параметры для выполнения задачи.

- Лучше всело предсказала ряд модель Ridge. Это означает, что модель в среднем ошибаетс на 34-35 заказа такси в час.

- По рейтингу на кросс валидации лучше всего себя показал LGBMRegressor.
