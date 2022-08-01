![](https://camo.githubusercontent.com/a2ac81a35fa82501f84d6ee52f4dedaffc233f32d5dfabe0a1074311a9be5be7/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313430302f302a75565030577745574f747048733430452e706e67)

# Яндекс Практикум - Проекты
Здесь собраны проекты, выполненные в Яндекс Практикуме на курсе "Специалист по Data Science".


|№ проекта|Проект|Название проекта|Библиотека|
|---|---|---|---|
|Project_01|[Предобработка данных](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_01)|Исследование надёжности заёмщиков — анализ банковских данных.|pandas, matplotlib, pymystem3|
|Project_02|[Исследовательский анализ данных](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_02)|Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости.|pandas, matplotlib|
|Project_03|[Статистический анализ данных](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_03)|Определение выгодного тарифа для телеком компании.|pandas, math, numpy, matplotlib, scipy|
|Project_04|[Сборный проект](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_04)|Исследование закономерности успеха игры.|pandas, numpy, matplotlib, scipy, seaborn |
|Project_05|[Введение в машинное обучение](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_05)|Классификаиция клиентов телеком компании.|pandas, numpy, sklearn(DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, DummyClassifier), time|
|Project_06|[Обучение с учителем](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_06)|Прогнозирование оттока клиента Банка.|pandas, matplotlib, numpy, sklearn(DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, OrdinalEncoder, StandardScaler), time|
|Project_07|[Машинное обучение в бизнесе](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_07)|Определение наиболее выгодного региона нефтедобычи.|pandas, numpy, sklearn(LinearRegression), scipy, matplotlib|
|Project_08|[Сборный проект](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_08)|Исследование технологического процесса очистки золота.|pandas, numpy, sklearn(LinearRegression, DecisionTreeRegressor, RandomForestRegressor, DummyRegressor, StandardScaler, Pipeline, GridSearchCV), matplotlib, random, warnings|
|Project_09|[Линейная алгебра](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_09)|Защита данных клиентов страховой компании.|pandas, numpy, sklearn(LinearRegression)|
|Project_10|[Численные методы (градиентный бустинг)](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_10)|Построение модели определения стоимости автомобиля.|pandas, numpy, matplotlib, seaborn, catboost(CatBoostRegressor), sklearn(GridSearchCV, RandomizedSearchCV, LabelEncoder, StandardScaler, RandomForestRegressor), lightgbm, time|
|Project_11|[Временные ряды](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_11)|Прогнозирование количества заказов такси на следующий час.|pandas, numpy, matplotlib, time, statsmodels, sklearn(TimeSeriesSplit, GridSearchCV, LinearRegression, RandomForestRegressor), catboost|
|Project_12|[Машинное обучение для текстов](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_12)|Обучение модели классификации комментариев.|pandas, re, matplotlib, tqdm, pymystem3, nltk(WordNetLemmatizer), sklearn(TfidfVectorizer, GridSearchCV, LogisticRegression, RandomForestClassifier, DecisionTreeClassifier, Pipeline), catboost, lightgbm, time, string, en_core_web_sm|
|Project_13|[Извлечение данных](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_12)|||
|Project_14|[Компьютерное зрение](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_12)|||
|Final_project|[Выпускной проект](https://github.com/bitfounder/Yandex-Practicum/tree/main/Project_12)|||




# Project_08
## Исследование технологического процесса очистки золота.
Подготовим прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используем данные с параметрами добычи и очистки.

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

Нам нужно:

Подготовить данные;
Провести исследовательский анализ данных;
Построить и обучить модель.

# Project_09
## Защита данных клиентов страховой компании.
Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.

Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.

# Project_10
## Построение модели определения стоимости автомобиля.
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости.

Заказчику важны:

 * качество предсказания;
 * скорость предсказания;
 * время обучения.

# Project_11
## Прогнозирование количества заказов такси на следующий час
Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

Нам нужно:

1. Загрузить данные и выполнить их ресемплирование по одному часу.
2. Проанализировать данные.
3. Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных.
4. Проверить данные на тестовой выборке и сделать выводы.

# Project_12
## Обучение модели классификации комментариев
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Обучим модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.

Построим модель со значением метрики качества F1 не меньше 0.75.
