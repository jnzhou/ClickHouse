# system.databases {#system-databases}

Таблица содержит один столбец name типа String - имя базы данных.
Для каждой базы данных, о которой знает сервер, будет присутствовать соответствующая запись в таблице.
Эта системная таблица используется для реализации запроса `SHOW DATABASES`.

[Оригинальная статья](https://clickhouse.tech/docs/ru/operations/system_tables/databases) <!--hide-->