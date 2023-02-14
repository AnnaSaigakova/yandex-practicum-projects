# Проект "Недвижимость"
Проект выполнен в ходе обучения в Яндекс.Практикуме (профессия "Аналитик данных") 

## Цель 
Анализ рыночной стоимости квартир на основании данных сервиса по операциям с недвижимостью. 

## Задачи
* Определение факторов, влияющие на стоимость недвижимости, на основании анализа площади, количества комнат, высоты потолков.
* Анализ стоимости жилья в зависимости от популярности населенного пункта.
* Анализ сегмента недвижимости в центре города.


## Данные
(архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет)
* расстояние до ближайшего аэропорта в метрах (м)
* число балконов
* высота потолков (м)
* расстояние до центра города (м)
* количество дней размещения объявления (от публикации до снятия)
* дата публикации
* этаж
* всего этажей в доме
* апартаменты (булев тип)
* площадь кухни в квадратных метрах (м²)
* цена на момент снятия с публикации
* жилая площадь в квадратных метрах (м²)
* название населённого пункта
* свободная планировка (булев тип)
* число парков в радиусе 3 км
* расстояние до ближайшего парка (м)
* число водоёмов в радиусе 3 км
* расстояние до ближайшего водоёма (м)
* число комнат
* квартира-студия (булев тип)
* площадь квартиры в квадратных метрах (м²)
* число фотографий квартиры в объявлении

## Используемые библиотеки
* *pandas*
* *matplotlib*
* *seaborn*
## Результат
* Определено среднее время продажи квартир;
* Определены характеристики основной массы квартир (площадь, стоимость, кол-во комнат, высота потолков);
* Выделен центральный сегмент жилья в г.Санкт-Петербург;
* Определены характеристики основной массы квартир центрального сегмента г.Санкт-Петербург;
* Сделан вывод о том, что на стоимость жилья влияет общая площадь, количество комнат, удаленность от центра и этаж;
* Сделан вывод о зависимости стоимости недвижимости от даты подачи объявления (дня недели, месяца, года).