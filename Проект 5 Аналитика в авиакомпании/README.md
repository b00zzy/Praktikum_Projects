Исследование данных о продаже билетов в авиакомпании с целью ответа на вопрос увеличивается пассажиропоток в дни крупнных фестивалей или нет

Имеющиеся на серверах авиакомпании данные:

информация об аэропортах:
+ трёхбуквенный код аэропорта
+ название аэропорта
+ город
+ временная зона

информация о самолётах:
+ код модели самолёта
+ модель самолёта
+ количество самолётов

нформация о билетах:
+ уникальный номер билета
+ персональный идентификатор пассажира
+ имя и фамилия пассажира

информация о рейсах:
+ уникальный идентификатор рейса
+ аэропорт вылета
+ дата и время вылета
+ аэропорт прилёта
+ дата и время прилёта
+ id самолёта

стыковая таблица «рейсы-билеты»
+ номер билета
+ идентификатор рейса

информация о фестивалях
+ уникальный номер фестиваля
+ дата проведения фестиваля
+ город проведения фестиваля
+ название фестиваля

Исследование проводилось в два этапа:

1) Запрос и агрегация данных с помощью **SQL** с серверов авиакомпании

2) Анализ полученных данных с использованием библиотек **pandas** и **matplotlib**:

+ предобработка данных не требовалась так как данные были получены нами запросами к БД
+ был проведен исследовательский анализ
