# **Прогнозирование количества заказов такси**
## Задача проекта
Разработка системы предсказания объема заказа.

## Инспользуемые иструменты 
- python
- pandas
- scikit-learn
  - sklearn.metrics
  - sklearn.model_selection
  - sklearn.ensemble
  - sklearn.preprocessing
- statsmodels.tsa.seasonal
- catboost
- lightgbm
- matplotlib

## Выводы
Мы подготовили признаки для обучения, затем обучили три модели: LghtGBM, Случайный лес и CatBoost. Подобрали сколько дополнительных признаков нам добавлять. Лучшей моделью на валидации вышла CatBoost. По условию необходимо получить ошибку менее 48 на тесте, чего мы и добились RMSE = 41.4.
