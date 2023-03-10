## Bank Customer Churn Prediction

#### Выполнили: 
Галеев Башир 11-003,\
Касимов Дамир 11-003,\
Хайбуллин Тагир 11-009

----

### Видеозащита и Блокнот на Google Disk
https://drive.google.com/drive/folders/1v5neDzOZPBSS1-D_fIV6C3F4tgq3kLz7

----

### Датасет
https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

#### Элементы датасета:

* CustomerId - уникальный ID клиентов банка
* Surname - Фамилии клиентов банка
* CreditScore - Кредитный рейтинг клиента
* Geography - Местонахождение клиента
* Gender - Пол
* Age - Возраст клиента
* Tenure - Время, с которого человек является клиентом банка
* Balance - Баланс на счету клиента
* NumOfProducts - Количество банковских продуктов, которыми пользуется клиент
* HasCrCard - Показатель, имеет ли данный клиент кредитную карту
* IsActiveMember - Является ли клиент активным
* EstimatedSalary - Предполагаемый заработок клиента
* Exited - Перестал ли человек быть клиентом банка

----

### Описание проблемы
Данный датасет представляет собой набор данных клиентов одного из банков США. На данный момент банк претерпевает большие убытки, из-за чего велика вероятность оттока клиентов.
Основываясь на данных клиентов, нам необходимо построить модель, которая будет максимально точно совершать прогноз, по которому будет видно, покинут банк те или иные клиенты или нет.

----
### Методы для прогнозирования

***Метод опорных векторов (The method of support vectors)*** - это метод машинного обучения, целью которого является попытка классифицировать входные наборы данных в один из двух классов.

***Метод К ближайших соседей (K-Nearest Neighbors Method)***  – это метрический алгоритм для автоматической классификации объектов или регрессии

***Деревья решений (Decision trees)***  – это статистический метод, позволяющий предсказывать принадлежность наблюдений или объектов к тому или иному классу категориальной зависимой переменной или среднее значение количественной переменной в зависимости от соответствующих значений одной или нескольких независимых переменных.

***XGBoost*** — Это специальная библиотека, предоставляющая функциональность для решения задач, связанных с регуляризацией градиентного бустинга.

----


### Heatmap данного датасета

![alt text](img.png?raw=true)

----

### Вывод

Исходя из наших исследований, мы можем утвержать, что предсказание оттока клиентов достаточно высоко. На данный момент точность правильного прогноза составляет 88%