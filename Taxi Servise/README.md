# Прогнозирование заказов для сервиса такси
[ipynb](https://github.com/veter11111/portfolio/blob/main/Taxi%20Servise/taxi_servise.ipynb)
## Описание проекта ##
Требовалось построить модель для прогнозирования количества заказов такси на следующий час с целью привлечения большего количества водителей в период пиковой нагрузки в аэропортах.

## Используемые библиотеки
- pandas 
- matplotlib.pyplot 
- statsmodels 
- sklearn
- catboost 

## Общий вывод
Был выполнен EDA. Обучены три модели - LinearRegression, RandomForestRegressor, CatBoostRegressor. Для определения качества моделей использовалась метрика RMSE. Лучшая модель проверена на тестовой выборке и рекомендована для предсказания количества заказов такси на следующий час.
