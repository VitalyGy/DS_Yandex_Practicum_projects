# Проект: Статистический анализ данных
Вы аналитик популярного сервиса аренды самокатов GoFast. Вам передали данные о некоторых пользователях из нескольких городов, а также об их поездках. Проанализируйте данные и проверьте некоторые гипотезы, которые могут помочь бизнесу вырасти.
Чтобы совершать поездки по городу, пользователи сервиса GoFast пользуются мобильным приложением. 
# Описание данных
В основных данных есть информация о пользователях, их поездках и подписках.  
## Пользователи — users_go.csv
* user_id	уникальный идентификатор пользователя
* name	имя пользователя
* age	возраст
* city	город
* subscription_type	тип подписки (free, ultra)  
## Поездки — rides_go.csv
* user_id	уникальный идентификатор пользователя
* distance	расстояние, которое пользователь проехал в текущей сессии (в метрах)
* duration	продолжительность сессии (в минутах) — время с того момента, как пользователь нажал кнопку «Начать поездку» до момента, как он нажал кнопку «Завершить поездку»
* date	дата совершения поездки  
## Подписки — subscriptions_go.csv
* subscription_type	тип подписки
* minute_price	стоимость одной минуты поездки по данной подписке
* start_ride_price	стоимость начала поездки
* subscription_fee	стоимость ежемесячного платежа
