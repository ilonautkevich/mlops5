Создано 3 датасета с нормальными данными и 1 с шумами

Обучена модель лишь на одном из датасетов с нормальными данными

Модель протестирована на всех датасетах (выведены метрики для всех наборов данных)

Созданы тесты для проверки основных частей кода с помощью ipytest

Также созданы были 4 теста, оценивающие mse различных датасетов, так как значение этой метрики сильно отклоняется при наличие шумов, мы можем ее использовать для идентификации такого датасета

Все тесты пройдены, кроме одного c шумами
