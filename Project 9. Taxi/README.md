## Прогнозирование заказов такси.

[HTML](https://github.com/SvetlanaaIvanova/Practicum_projects/blob/main/Project%209.%20Taxi/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2%20%D1%82%D0%B0%D0%BA%D1%81%D0%B8.html)

[ipynb](https://github.com/SvetlanaaIvanova/Practicum_projects/blob/main/Project%209.%20Taxi/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2%20%D1%82%D0%B0%D0%BA%D1%81%D0%B8.ipynb)

### Описание проекта
На основе данных о заказах такси в аэропортах требуется построить модель для предсказания количества заказов такси на следующий час для регулирования числа водителей в период пиковых нагрузок.

### Навыки и инструменты
- python
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn.model_selection
- sklearn.pipeline
- sklearn.linear_model
- sklearn.tree
- sklearn.preprocessing
- sklearn.metrics
- sklearn.compose
- catboost
- GridSearchCV
- TimeSeriesSplit
- statsmodels.tsa.seasonal
- statsmodels.tsa.stattools
- phik  

### Общий вывод
Проведен анализ временных рядов и сформированы новые признаки на основе исходных. Обучены и оценены 4 модели регрессии (модели линейной регресии с регуляризацией Lasso и Ridge, регрессия дерева решений и CatBoostRegressor), лучшие результаты среди которых показала модель линейной регресии с L2-регуляризацией при силе регуляризации = 0.1 (стандартная ошибка в размере 27 на тренировочных данных и 43 - на тестовых).

