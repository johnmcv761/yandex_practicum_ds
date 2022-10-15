# 16.	Прогноз оттока клиентов. финал

**Задача**

Отток клиентов Это когда существующий клиент, пользователь, подписчик или любой другой клиент перестает вести бизнес или прекращает отношения с компанией.
Типы оттока клиентов:
Контрактный отток - клиент находится под контрактом на услугу и решает отменить услугу, например, кабельное телевидение.
Добровольный отток - когда пользователь добровольно отменяет услугу, например, сотовую связь.
Неконтрактный отток - когда клиент не имеет контракта на услугу и решает отменить услугу, например, лояльность потребителей в розничных магазинах.
Непроизвольный отток - когда отток происходит без какого-либо запроса клиента, например, истечение срока действия кредитной карты.
Причины добровольного оттока
1.	Отсутствие использования
2.	Плохое обслуживание
3.	Лучшая цена
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. 

**Данные**

Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

Оператор предоставляет два основных типа услуг:

1.	Стационарную телефонную связь. Возможно подключение телефонного аппарата к нескольким линиям одновременно.
2.	Интернет. Подключение может быть двух типов: через телефонную линию (DSL, от англ. digital subscriber line, «цифровая абонентская линия») или оптоволоконный кабель (Fiber optic).
Также доступны такие услуги:
1.	Интернет-безопасность: антивирус (DeviceProtection) и блокировка небезопасных сайтов (OnlineSecurity);
2.	Выделенная линия технической поддержки (TechSupport);
3.	Облачное хранилище файлов для резервного копирования данных (OnlineBackup);
4.	Стриминговое телевидение (StreamingTV) и каталог фильмов (StreamingMovies).
Данные состоят из файлов, полученных из разных источников:
•	contract.csv — информация о договоре;
•	personal.csv — персональные данные клиента;
•	internet.csv — информация об интернет-услугах;
•	phone.csv — информация об услугах телефонии.
Во всех файлах столбец customerID содержит код клиента.
Информация о договорах актуальна на 1 февраля 2020.

**План**

1. Знакомство с данными
2. Предобработка данных
3. Обучение моделей
4. Вывод

**Инструменты**

Python, Pandas, Matplotlib, Scikit-learn