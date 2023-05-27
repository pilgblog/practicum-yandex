# Определение возраста покупателей. Компьютерное зрение.
## Цель проекта:
Построить модель, которая по фотографии определит приблизительный возраст человека. В распоряжении набор фотографий людей с указанием возраста.
## Инструменты:
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" width="50" height="60"/>&nbsp;
  <img src="https://github.com/scikit-learn/scikit-learn/blob/main/doc/logos/scikit-learn-logo.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="React" alt="React" width="50" height="60"/>&nbsp;
</div>

## Вывод:

Мы построили и обучили свёрточную нейронную сеть на датасете с фотографиями людей. Добились значения MAE на тестовой выборке 7. При обучении модели воспользовались архитектурой ResNet50 с оптимизатором adam при шаге lr=0.00002, в конце архитекруры не добавляли два слоя в верхушке, сконтруировали ее заново. Применили аугментацию на обучающей выборке отражение по горизонтали, значение MAE составила 7,6, модель обучилась на 6 эпохах.
