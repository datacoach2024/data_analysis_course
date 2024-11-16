# Case Study по модулю Plotly  

Ваша задача - провести **разведочный анализ** (Exploratory Data Analysis) датасета [Adventure Works](https://github.com/datacoach2024/data_analysis_course/blob/main/data/adventure_works.xlsx), используя SQL, pandas и plotly. Цель - проанализировать клиентскую базу, тренды продаж и характеристики продуктов чтобы выявить ***<ins>полезные инсайты</ins>*** для бизнеса.  

## 1. Знакомство со структурой данных  
1.1 Проведите обзор таблиц, которые будут задействованы в вашем анализе, а именно:
  * отобразите выборку датафреймов таблиц (10 строк)
  * укажите размер каждой таблицы

1.2 Проверьте таблицы на наличие пустых значений, и решите что с ними делать. Напишите обоснование своего решения.  
1.3 Проверьте типы данных столбцов в таблицах. В случае несоответствия типа данных содержимому столбцов, приведите их к соответствующему типу.  
1.4 Покажите базовую статистику по каждой таблице - например количество значений, max, min, median, mode, количество уникальных значений и т.д.

## 2. Анализ клиентской базы  
2.1 Визуализируйте распределение возраста клиентов с помощью гистограммы и коробочной диаграммы (boxplot). Опишите ваши наблюдения.  
2.2 Проверьте распределение на наличие выбросов и решите что с ними делать. Напишите обоснование своего решения.  
2.3 Создайте диаграммы для отображения разбивки клиентов по регионам и странам. Опишите ваши наблюдения.  
2.4 Визуализируйте распределение персонального дохода клиентов в целом и в разбивке по полу, семейному положению, сфере деятельности и регионам. Опишите ваши наблюдения.  

## 3. Анализ продуктов и продаж   
3.1 Отобразите на диаграмме общую сумму продаж по месяцам и годам. Опишите наблюдается ли в данных сезональность (т.е. есть ли периоды в которых продажи регулярно падают или наоборот растут) и какой прослеживается тренд продаж.  
3.2 Создайте диаграммы, отображающие сумму продаж в разбивке по продуктам, категориям и годам. Определите топ 5 наиболее продаваемых продуктов.  Напишите обоснование своего решения.  
3.3 Визуализируйте распределение цены продуктов и коррелюцию цены и суммы продаж. Опишите свои наблюдения.  
3.4 Разбейте клиентскую базу на сегменты по частоте и общей сумме покупок. Визуализируйте полученные сегменты с помощью диаграмм. Напишите какой сегмент вы считаете наиболее приоритетным и обоснуйте своё решение.  

---  

Решение должно быть в формате `jupyter notebook`. Файл должен называться `eda_case_study.ipynb`.    
Ноутбук должен содержать заголовок **Case Study по модулю Plotly**, имя и фамилию исполнителя и дату исполнения.    

> Данные должны храниться в виде связанных таблиц в базе данных откуда и должно производиться их чтение.  

Структура ноутбука должна быть следующей:  
* название блока
* номер и описание задачи
* код решения
* ваши выводы по полученным результатам

---  
Создайте файл `eda_summary_report.md`. В этом файле напишите аналитическую записку по резултатам проведённого анализа. Вам нужно описать что вы сделали, какие результаты получили и к каким выводам пришли.  Используйте markdown разметку. 

---  
Создайте в вашем репозитории новую ветку и сохраните оба файла (`eda_case_study.ipynb`, `eda_summary_report.md`). Сделайте соответствующие коммиты, пуш и создайте pull request. В классруме прикрепите скриншот вкладки `files changed` вашего pull request-а и ссылку на репозиторий.