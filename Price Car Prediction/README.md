# Определение рыночной стоимости автомобилей 
 [ipynb](https://github.com/veter11111/portfolio/blob/main/Price%20Car%20Prediction/price_car_prediction.ipynb)
## Описание проекта ##
Требуется построить модель, которая умеет определять рыночную стоимость автомобиля. Для заказчика важны: качество предсказания, скорость предсказания, время обучения.

## Используемые библиотеки
- pandas 
- numpy
- matplotlib.pyplot 
- lightgbm 
- sklearn
- catboost 
- time

## Общий вывод
Был проведен EDA. Были обучены модели LinearRegression, LGBMRegressor, CatBoostRegressor, RandomForestRegressor. Для определения качества моделей использовалась метрика RMSE. Модель с лучшим качеством и временем предсказания была проверена на тестовой выборке и рекомендована заказчику для предсказания рыночной стоимости автомобиля.
