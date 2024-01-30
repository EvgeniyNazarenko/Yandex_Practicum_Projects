# Описание проекта
Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания. Значение метрики RMSE на тестовой выборке должно быть не больше 48.

# Навыки и инструменты.
-pandas

-numpy

-sklearn.model_selection.RandomizedSearchCV

-sklearn.model_selection.TimeSeriesSplit

-sklearn.model_selection.train_test_split

-sklearn.linear_model.LinearRegression

-sklearn.ensemble.RandomForestRegressor

-sklearn.metrics.mean_squared_error

-catboost.CatBoostRegressor

-lightgbm.LGBMRegressor

-statsmodels.tsa.seasonal.seasonal_decompose

-matplotlib

-optuna

# Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Обучены 4 модели с перебором гипер параметров:Линейная регрессия ,случайного леса, Catboost,LgbLight. Лучшее значение RMSE на валидационной выборке показала линейная регрессия. RMSE по тестовой выборке оказался в пределах поставленной задачи.
