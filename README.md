Задание №1

Постановка:  Имеется таблица с 7 цветами: 

Красный
Зеленый
Синий
Желтый
Фиолетовый
Пурпурный
Белый

Необходимо получить все возможные УНИКАЛЬНЫЕ пары этих цветов (Красный-Синий и Синий-Красный - это одна и та же пара цветов), цвета должны быть разными (Красный Красный и т.п. исключить).

Задание №2
Постановка:  Имеется таблица:

CREATE TABLE call 
  ( 
     subscriber_name VARCHAR(64) NOT NULL, 
     event_date      DATETIME NOT NULL, 
     event_cnt       INT NOT NULL 
  ) 

Требуется написать запрос, возвращающий для каждого абонента минимальную дату, когда количество событий по абоненту было максимально, и максимальную дату, когда количество событий по абоненту было минимально, а также количество событий.




Оценка: В качестве решения принимается скрипт для Oracle (SQL) с генерацией тестовых данных и решением задачи.

Дополнительные плюсы: наличие нескольких вариантов решений.
