# Прогнозирование продаж в магазинах офлаин-ритейлера в США

Построить модель прогнозирования спроса (продаж) на товары в магазинах
офлаин-ритейлера в США. Всего в датасете 3 магазина, в каждом по 15 артикулов
(товаров). Нужно выбрать 1 магазин (любой из 3). Прогнозировать продажи нужно на
неделю, месяц и квартал. В качестве дополнительной информации переданы данные о
цене товара (меняются раз в неделю), а также о праздниках в США.

Задание 1. Реализовать класс, который умеет:

1) предобрабатывать исходные данные в удобный формат;

2) обучаться для задачи прогнозирования;

3) оценивать качество своих прогнозов;

4) сохранять модели и подгружать их;

5) прогнозировать продажи на неделю, на месяц и на квартал.

Должна быть рабочая программа, которая делает инференс (прогнозирование на
произвольном тестовом датасете, аналогичном тому, который есть).

Задание 2. Подготовить отчет о решении данной задачи в виде Jupyter ноутбука. В
отчете, в частности, ответить на следующие вопросы:

1) Какие методы предобработки данных использовали?

2) Какие модели пробовали? Почему пробовали именно их?

3) Как проверяете качество модели? На каких данных? Какие метрики используюте?
Чем обусловлен выбор именно этих метрик?

4) Какое итоговое качество модели на тестовом датасете?
