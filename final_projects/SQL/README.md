# Анализ базы данных с помощью SQL-запросов

## Данные

1. Таблица `books` содержит данные о книгах:
- _book_id_ — идентификатор книги;
- _author_id_ — идентификатор автора;
- _title_ — название книги;
- _num_pages_ — количество страниц;
- _publication_date_ — дата публикации книги;
- _publisher_id_ — идентификатор издателя.

2. Таблица `authors` содержит данные об авторах:
- _author_id_ — идентификатор автора;
- _author_ — имя автора.

3. Таблица `publishers` содержит данные об издательствах:
- _publisher_id_ — идентификатор издательства;
- _publisher_ — название издательства;

4. Таблица `ratings` содержит данные о пользовательских оценках книг:
- _rating_id_ — идентификатор оценки;
- _book_id_ — идентификатор книги;
- _username_ — имя пользователя, оставившего оценку;
- _rating_ — оценка книги.

5. Таблица `reviews` содержит данные о пользовательских обзорах:
- _review_id_ — идентификатор обзора;
- _book_id_ — идентификатор книги;
- _username_ — имя автора обзора;
- _text_ — текст обзора.

## Задача

На основе данных провести анализ базы данных выпущенных книг, используя язык запросов SQL.

## Используемые библиотеки

- `Pandas`
- `SQLAlchemy`
