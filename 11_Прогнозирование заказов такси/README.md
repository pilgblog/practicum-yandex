# Прогнозирование закахзов такси
## Цель проекта:
Разработать систему предсказания объема заказа.
## Задачи проекта:
Задача регрессии, временные ряды, предсказать объем заказа.
## Инструменты:
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" width="50" height="60"/>&nbsp;
  <img src="https://github.com/scikit-learn/scikit-learn/blob/main/doc/logos/scikit-learn-logo.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
</div>

## Вывод:

Мы изучили исторические данные о заказах такси в аэропортах. Мы сделали ресемплирование по одному часу и проанализировали данные, взяв признаки за день и за час, обучили разные модели с различными гиперпараметрами. Мы спрогнозировали количество заказов такси на следующий час с минимальным значением RMSE на тестовой выборке 41.8 модели градиентоного бустинга библотеки CatBoost.
