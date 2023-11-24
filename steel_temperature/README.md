# **Оптимизация производственных расходов для металлургического комбината**
## Задача проекта
Построить модель, которая предскажет температуру стали.

## Инспользуемые иструменты 
- python
- pandas
- numpy
- matplotlib
- scikit-learn
  - sklearn.metrics
  - sklearn.model_selection
  - sklearn.ensemble
  - sklearn.preprocessing
  - sklearn.linear_model 
- catboost
- seaborn
- scipy.stats
- shap

## Выводы
Итоговой моделью была выбрана CatBoostRegressor, на тестовой выборке она показала MAE = 6.78, т.е. в среднем модель ошибается на 6,78 градусов.

