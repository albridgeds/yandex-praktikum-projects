# Токсичные комментарии (toxic_comments)
Проект выполнен в рамках спринта "Машинное обучение для текстов"

------------------------------------------------------------------------

### Задача проекта
Обучение модели для распознавания токсичных комментариев
Для оценки качества модели использовать метрику F1, значение должно быть не менее 0,75


### Исходные данные
- text — текст комментария
- toxic — токсичный ли комментарий (целевой признак)


### Используемые библиотеки
pandas, numpy, matplotlib, sklearn, nltk, re, tqdm.


### Основные пункты исследования
- загрузка данных и обзор признаков
- подготовка комментариев: очистка текста с помощью регулярных выражений, лемматизация
- выделение обучающей и тестовой выборки
- подбор модели с использованием кросс-валидации и поиска по сетке (метод GridSearchCV) и разными вариантами борьбы с дисбалансом. Исследованы модели: логистическая регрессия, SGD, Ridge Classifier, дерево решений
- обучение и проверка выбранной модели на тестовой выборке, проверка на адекватность


Проект завершен