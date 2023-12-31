# Исследование объявлений о продаже квартир

### Статус проекта
Проект завершен

### Цель исследования
Необходимо провести анализ данных сервиса Яндекс.Недвижимость, который поможет установить параметры, влияющие на цену объектов.

### Результат исследования
*На цену квартиры влияет:*
1. Общая площадь, с увеличением общей площади стоимость жилья растет.
2. Жилая площадь (тесно связана с общей площадью), с увеличением, цена растет.
3. Количество комнат (тесно связана с общей площадью), с увеличением, цена растет.
4. День недели и месяц публикации.
5. Отдаленность от центра - с увеличением расстояния от центра цена квартиры уменьшается.

*На цену 1 кв.м влияет:*
1. Количество комнат, начиная со студий до 3 комнатных квартир цена за 1 кв.м снижается с увеличением количества комнат.
2.Общая площадь - с увеличением площади цена снижается.
3.Тип этажа - на первом этаже самая низкая цена за 1 кв.м, на среднем - самая высокая.
4. День недели и месяц публикации
5. Зависит от населенного пункта, самые дорогой кв.м. в Санкт-Петербурге

*Для более точного анализа данных не хватает данных:*
1. Тип дома (кирпичный, панельный, сталинский, монолитный)
2. Оценка ремонта квартиры
3. Тип оплаты (доступна ли ипотека или оплата наличными)
4. Расстояние до метро
5. Близость к загруженным дорогам
6. Водопровод (есть ли горячая вода или нужно использовать газовую колонку)

### Стек
`pandas` `matplotlib` `seaborn`

