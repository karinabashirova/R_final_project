# R_final_project
В файлах .rmd содержится исходный код с комментариями. Файлы .html прелставляют собой скомпилированную версию кода, открываются в нормальном виде при загрузке в браузере.

1 Задание
В итоговом задании вы будете использовать данные переписи США. Целевая переменная: доход
респондента выше или ниже 50000$ в год.
1.1 Создайте новый скрипт RMarkdown.

1. Загрузите датасет Practice_08_dataset.rds
2. Разделите выборки на train/test с соотношением 0.7
3. Зависимая (целевая) переменная: Target

1.2 Моделирование

1. Вам необходимо построить три модели:
1. Стандартная модель (без caret, сэмплирования или кросс-валидаций)
2. Модель с сэмплированием (оверсэмплинг или SMOTE)
3. Модель с сэмплированием (оверсэмплинг или SMOTE) и кросс-валидацией (метод: cv; число
фолдов: 5)
• Рекомендуемые алгоритмы: дерево, случайный лес, полностью случайный лес, XGBoost.
• Вы можете использовать один и тот же алгоритм не больше двух раз
2. Для каждой модели вам необходимо получить прогноз и построить матрицу сопряженности
3. Подведите итоги какая модель оказалась наилучшей


2 Оформление отчета

Отчет необходимо оформить в RMarkdown и скомпилировать в HTML или Word. Отключите warning и
message в куске кода (чанке) с подключением пакетов. Скрывать код (echo) из отчета не нужно.

3 О наборе данных для итогового задания

Данные переписи США за 1995 год
Целевая переменная:
• fac - Target - Бинарная переменная годовой доход: больше 50000$/год или меньше 50000$/год

Независимые переменные:

• num - Age - Возраст

• fac - Workclass - Сфера занятости

• fac - Education - Образование

• num - Education_num - Образование, число лет

• fac - Martial_status - Семейное положение

• fac - Occupation - Профессия

• fac - Race - Раса

• fac - Sex - Пол

• num - Hours_Per_Week - Сколько часов в неделю работает

• fac - Native_Country - Родная страна
