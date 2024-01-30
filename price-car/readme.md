# Описание проекта
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Постройте модель, которая умеет её определять. В вашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей. Критерии, которые важны заказчику: качество предсказания; время обучения модели; время предсказания модели.

# Навыки и инструменты
-pandas

-matplotlib.pyplot

-time

-sklearn.preprocessing.OrdinalEncoder

-sklearn.model_selection.RandomizedSearchCV

-sklearn.metrics.mean_squared_error

-sklearn.model_selection.train_test_split

-sklearn.preprocessing.StandardScaler

-CatBoostRegressor

-LGBMRegressor

-lightgbm

-sklearn.linear_model.LinearRegression

-sklearn.compose.ColumnTransformer

-sklearn.pipeline

-sklearn.ensemble.RandomForestRegressor

- optuna

# Общие вывод

В ходе  исследования была изучена база данных по продажам автомобилей и обучены 4 модели: линейная регрессия , модель случайного леса , catboost , lgblight. Метрикой качества модели была метрика RMSE и время обучения для прогнозирования их цены.Найбольшую точность показала модель LGBlight , однако и время обучения у нее также было самым высоким.
