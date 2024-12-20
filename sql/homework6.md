# Домашка по созданию и редактированию таблиц в SQL  

1. Создайте таблицу `students`. Заполните её данными из нашей группы в телеграме. Таблица должна содержать следующие поля:
*student_id*, *student_name*, *username*, *bio*, *mobile*, *has_picture (есть ли фото профиля)*.
2. Создайте таблицу `lessons`. Таблица должна содержать следующие поля: *lesson_id*, *lesson_name*, *lesson_date*, *attendance (был, не был)*. Внесите в таблицу информацию об уроках, которые были пройдены в рамках модуля SQL.
3. Создайте таблицу `scores`. Таблица должна содержать следующие поля: *score_id*, *user_id*, *lesson_id*, *score*. Внесите в неё оценки, которые вы получили за выполненные домашние задания. Если по-какой либо домашке вы [ещё] не получили оценки - оставьте поле score пустым. Свяжите таблицу `scores` с таблицами `students` и `lessons` по внешним ключам.
4. В таблице `students` добавьте индекс к столбцу *username*.
5. Создайте представление `my_results`, которое будет возвращать **ваш**: *student_id*, *student_name*, *username*, *mobile*, *lessons_attended (количество уроков на которых вы присутствовали)*, *avg_score(средняя оценка за все домашки)*.

Создайте в вашем репозитории новую ветку и сохраните файл с кодом решения перечисленных задач в эту ветку.  
Сделайте коммит, пуш и создайте pull request. В классруме прикрепите скриншот вкладки files changed вашего pull request-а.
