# 11. Определение стоимости автомобилей

**Задача**

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Нужно построить модель для определения стоимости.
Заказчику важны:
1. Качество предсказания;
2. Скорость предсказания;
3. Время обучения.

**Данные**

В распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.
DateCrawled — дата скачивания анкеты из базы
VehicleType — тип автомобильного кузова
RegistrationYear — год регистрации автомобиля
Gearbox — тип коробки передач
Power — мощность (л. с.)
Model — модель автомобиля
Kilometer — пробег (км)
RegistrationMonth — месяц регистрации автомобиля
FuelType — тип топлива
Brand — марка автомобиля
NotRepaired — была машина в ремонте или нет
DateCreated — дата создания анкеты
NumberOfPictures — количество фотографий автомобиля
PostalCode — почтовый индекс владельца анкеты (пользователя)
LastSeen — дата последней активности пользователя
Целевой признак
Price — цена (евро)

**Инструменты**

Python, Pandas, Matplotlib, исследовательский анализ, визуализация данных, предобработка данных, seaborn, train_test_split, GridSearchCV, cross_val_score, RandomizedSearchCV, OrdinalEncoder, StandardScaler, LinearRegression, Ridge, DecisionTreeRegressor, RandomForestRegressor, GradientBoostingRegressor, CatBoostRegressor, LGBMRegressor, lgb, SVR, DummyRegressor, scipy stats, metrics, mean_squared_error, r2_score, mean_absolute_error, make_scorer

**Статус**

Закончен. Возможно улучшение и оптимизация.