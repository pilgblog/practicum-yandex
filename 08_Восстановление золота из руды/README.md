# Восстановление золота из руды
## Цель проекта:
Спрогнозировать концентрацию золота при проведении процесса очистки золота
## Задачи проекта:
Проведести предобработку данных и их анализ. Задача регрессии, кастомные метрики

## Инструменты:
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/whitead/skunk/main/tests/skunk.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://github.com/numpy/numpy/blob/main/branding/logo/primary/numpylogo.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://github.com/valohai/ml-logos/blob/master/scipy.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
</div>

## Вывод:

Мы исследовали датасеты, на которых построили модель, которая поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. Для этого мы проанализировали данные концентрации металлов и выяснили, что после каждого этапа концентрация метталов свинца и золота увеличивались, а серебра уменьшались. Затем мы визуализировали данные по размеру гранул и обнаружили, что с каждей стадией они изменялись в меньшую сторону. Затем мы с помощью кросс-валидации выбрали наилучшую модель Случайный лес и сделали предсказания, чтобы посчитать итоговое smape. Итоговая sMAPE на тестовой выборке 9,08, по сравнению с константной моделью 8,88, мы сделали вывод что модель приемлема.
