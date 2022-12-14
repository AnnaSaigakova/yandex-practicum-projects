# Проект "Исследование оттока клиентов фитнес-клуба"
Проект выполнен в ходе обучения в Яндекс.Практикуме (профессия "Аналитик данных") 

## Цель
Провести анализ и подготовить план действий по удержанию клиентов сети фитнес-центров.

## Задачи
* Построить модель прогнозирования вероятности оттока для каждого клиента;
* Сформировать типичные портреты пользователей: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
* Проанализировать основные признаки, наиболее сильно влияющие на отток;
* Сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами.

## Данные
***Данные пользователя за предыдущий до проверки факта оттока месяц:***

* пол;
* признак проживания или работы в районе, где находится фитнес-центр;
* сотрудник компании-партнёра клуба;
* факт первоначальной записи в рамках акции «приведи друга»;
* наличие контактного телефона;
* возраст;
* время с момента первого обращения в фитнес-центр (в месяцах).

***Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента***

* длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год);
* срок до окончания текущего действующего абонемента (в месяцах);
* факт посещения групповых занятий;
* средняя частота посещений в неделю за все время с начала действия абонемента;
* средняя частота посещений в неделю за предыдущий месяц;
* суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон.

## Используемые библиотеки
* *pandas*
* *numpy*
* *matplotlib*
* *seaborn*
* *scikit-learn*
* *scipy*
## Результат
* Для прогнозирования оттока построена модель на основе логистической регресии (посетители фитнес-центра разделены на кластеры по уровню надежности);
* Выделены наиболее важные признаки для выявления клиентов, склонных к оттоку;
* Определен портрет посетителя фитнес-центра, склонного к оттоку;
* Сформулированы базовые рекомендации по работе с клиентами для отдельных кластеров посетителей фитнес-центра.



