## Определение стоимости автомобилей.

[HTML](https://github.com/SvetlanaaIvanova/Practicum_projects/blob/main/Project%208.%20Cars/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D0%B5%D0%B9.html)

[ipynb](https://github.com/SvetlanaaIvanova/Practicum_projects/blob/main/Project%208.%20Cars/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D0%B5%D0%B9.ipynb)

### Описание проекта
На основе исторических данных об автомобилях (технические характеристики, комплектации, цены) требуется построить модель для определения их стоимости для разработки приложения с целью привлечения новых клиентов.

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
- sklearn.impute
- RandomizedSearchCV
- CatBoostRegressor
- LGBMRegressor
- phik  

### Общий вывод
Обучены и оценены 4 модели регрессии (модель линейной регресии, регрессии дерева решений, LightGBM и CatBoostRegressor), лучшие результаты среди которых показала модель CatBoostRegressor со значением стандартной ошибки в размере 1733 (1695 - не тестовой выборке). Проведен анализ важности признаков: наибольшее влияние на прогноз имеет признак регистрации автомобиля, а также показатель мощности автомобиля в лошадиных силах.
