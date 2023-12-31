# Тестовое задание на операционного аналитика

### Описание задачи

К вам приходит CEO Кухни на районе и просит за несколько дней изучить влияния времени доставки заказа на поведение пользователей.

Ваш коллега уже сделал выгрузку данных и прислал вам csv файлы с ними.

### Данные

- Файл с описанием продаж за 2 недели на нескольких кухнях (цифры рандомно исправлены). Одна строка - один заказ.
    - date - время создания заказа;
    - user - идентификатор клиента;
    - kitchen_id - id кухни;
    - revenue - Выручка в рублях;
    - items_quantity - Количество товаров в заказе;

[sales_test.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6439e4b8-5edf-4bc5-b9d2-148d9832e2ec/sales_test.csv)

- Файл с данными по времени доставки. Одна строка - один заказ.
    - date - время создания заказа;
    - user - идентификатор клиента;
    - delivery_time - время доставки заказа (минуты);
    - delay - отклонение от ожидаемого времени доставки;
        - отрицательные значения означают, что заказ доставлен раньше обещанного клиенту времени
        - положительные, что позже.

[deliveries_test.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fcfad9c7-308a-49b5-aaff-759a389b6a27/deliveries_test.csv)

### Задание

Проведите исследовательский анализ данных, сделайте визуализацию и выводы.

### Вопросы

1. Предложите набор метрик, по которым вы будете оценивать изменение поведения клиентов.

2. Ответьте:
    - Влияет ли скорость доставки на поведение клиентов?
    - Влияет ли наличие сильных опозданий на поведение клиентов?
    - Что считать сильным опозданием?
