# -
база данных неисправностей лазерных принтеров (пример неисправности дефекта лазерной печати).
Приложение создано фрейморком qtc использование языка программирование с++  и базы данных postgres sql.
Приложение построено в виде таблиц к каждой неиспраности, если какой-то таблицы еше нет в базе то она создается и будет показана в окне приложения, перед пользователем.
Если нет таблицы в базе выполняется три запроса: создание таблицы, заполнение таблицы данными и выборка таблицы, если таблица уже есть в базе выполняется только ее выборка
