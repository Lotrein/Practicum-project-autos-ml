[**RUS**]

**Описание учебного проекта**

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Вам нужно построить модель для определения стоимости. 
Заказчику важны:
- качество предсказания;
- скорость предсказания;
- время обучения.

**Инструкция по выполнению проекта**

Чтобы усилить исследование, не ограничивайтесь градиентным бустингом. Попробуйте более простые модели — иногда они работают лучше. Это редкие случаи, которые легко пропустить, если всегда применять только бустинг. Поэкспериментируйте и сравните характеристики моделей: скорость работы, точность результата.
- Загрузите и подготовьте данные.
- Обучите разные модели. Для каждой попробуйте различные гиперпараметры.
- Проанализируйте скорость работы и качество моделей.

**Примечания**:

- Для оценки качества моделей применяйте метрику RMSE.

**Описание данных**

Данные находятся в файле /datasets/autos.csv.
**Признаки**
- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- NotRepaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя

**Целевой признак**
- Price — цена (евро)

---

[**ENG**]

**Educational Project Description**

The used car sales service "Not damaged, not painted" is developing an application to attract new customers. It enables users to quickly find out the market value of their car. You have access to historical data including technical specifications, configurations, and car prices. Your task is to build a model to determine the value of a car. Important factors for the client include:
- Prediction quality;
- Prediction speed;
- Training time.

**Project Execution Instructions**

To enhance the research, do not limit yourself to gradient boosting. Try simpler models—sometimes they perform better. These rare cases can be easily missed if you only use boosting. Experiment and compare the characteristics of the models: operational speed and accuracy of the results.
- Load and prepare the data.
- Train different models. Try various hyperparameters for each.
- Analyze the speed and quality of the models.

**Notes**:

- Use the RMSE metric to evaluate model quality.

**Описание данных**

The data is in the file /datasets/autos.csv.
**Признаки**
- DateCrawled — the date the listing was downloaded from the database
- VehicleType — the type of vehicle body
- RegistrationYear — the year the car was registered
- Gearbox — type of transmission
- Power — power (hp)
- Model — car model
- Kilometer — mileage (km)
- RegistrationMonth — the month the car was registered
- FuelType — type of fuel
- Brand — car brand
- NotRepaired — whether the car was repaired or not
- DateCreated — the date the listing was created
- NumberOfPictures — number of car photos
- PostalCode — postal code of the listing owner (user)
- LastSeen — the date of the user's last activity

**Target Feature**
- Price — price (euros)
