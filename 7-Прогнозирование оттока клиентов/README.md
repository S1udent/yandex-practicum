# Прогнозирование оттока клиентов
## Описание проекта

В нашем распоряжении исторические данные о поведении клиентов и расторжении договоров с банком. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.
## Вывод
Протестировав разные модели с различными гиперпараметрами и методами баланса класснов, по метрике F1, равной 0.615 на валидационной выборке и методом увеличения тренировочной выборки, была протестирована тестовая выборка. По результатам теста мы получили F1 = 0.614, AUC-ROC = 0.853. AUC-ROC говорит об отличии от случайной модели и средней доли истинно положительных ответов.
## Решение
[Открыть Notebook](https://github.com/S1udent/yandex-practicum/blob/main/7-Прогнозирование%20оттока%20клиентов/Прогнозирование%20оттока%20клиентов.ipynb)
