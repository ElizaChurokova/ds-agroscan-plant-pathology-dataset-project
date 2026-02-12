# Классификация болезней растений с помощью нейросетей

Сравнительный анализ трех архитектур (InceptionV3, ResNet50, EfficientNet-B0) для автоматической диагностики заболеваний на основе датасета PlantPathology.

##  Основные результаты
В ходе исследования было проведено сравнение моделей по точности и скорости работы:

* **InceptionV3:** 96.91% Accuracy — **Лучшая по точности.**
* **EfficientNet-B0:** 96.55% Accuracy — **Лучшая по балансу скорости и веса.**
* **ResNet50:** 95.27% Accuracy.

##  Аналитика
В проекте использовался метод **Transfer Learning** и механизм **Early Stopping** для предотвращения переобучения. Подробные графики обучения и матрицы ошибок представлены внутри ноутбуков.

##  Структура репозитория
* `Data_Preprocessing.ipynb` — код разделения и подготовки данных.
* `Models_Training_Comparison.ipynb` — основной код с обучением и сравнением трех моделей.

##  Ссылка на веса моделей (.keras)
EfficientNet_B0 model: https://drive.google.com/file/d/1nJyttKHFRYxp9eaaJuaQVECn3HckTAqC/view?usp=drive_link
InterceptionV3 model: https://drive.google.com/file/d/1FKNszbxciJ8lFrQfJ_GaQhZI11AG6qlY/view?usp=drive_link
ResNet50 model: https://drive.google.com/file/d/1rLxWq0Ojv3Fdcj76dmjhqogDO6WU9DtY/view?usp=drive_link

##  Ссылка на разделенный датасет (train, val, test)
plant_dataset_split: https://drive.google.com/drive/folders/1AOm9tkKVvdUYuQwD7e56KbuZuuVJvvSe?usp=drive_link


