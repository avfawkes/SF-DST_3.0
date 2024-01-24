<img src = https://github.com/avfawkes/SF-DST_3.0/blob/main/Project2_SQL/hh_label.jpg alt="drawing" style="width:400px;">

# PROJECT-2. Анализ вакансий из HeadHunter

![Jupyter](https://img.shields.io/badge/Jupyter-%23f37726?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458?logo=pandas&logoColor=white)
![Psycopg2](https://img.shields.io/badge/Psycopg2-%23009977)
![Requests](https://img.shields.io/badge/Requests-%23989898)
![BeatifullSoap](https://img.shields.io/badge/BeatifullSoap-%23878b8c)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%2330668f?logo=postgresql&logoColor=white)

## Оглавление

- [Задача](https://github.com/avfawkes/SF-DST_3.0/main/Project2_SQL/README.md#Задача)  
- [Структура данных](https://github.com/avfawkes/SF-DST_3.0/main/Project2_SQL/README.md#Структура-данных)  
- [Этапы работы над проектом](https://github.com/avfawkes/SF-DST_3.0/main/Project2_SQL/README.md#Этапы-работы-над-проектом)  
- [Результат](https://github.com/avfawkes/SF-DST_3.0/main/Project2_SQL/README.md#Результат)  

### Задача
Необходимо подключиться к базе данных с вакансиями портала HeadHunter и исследовать их с целью создания в дальнейшем рекомендательной системы.

### Структура данных  
Данные были получены с портала [`HeadHunter`](https://hh.ru/). Они представлены в виде 5 таблиц и хранятся в базы данных компании [`Skillfactory`](https://skillfactory.ru).
Схема данных:
![](https://github.com/avfawkes/SF-DST_3.0/blob/main/Project2_SQL/data_scheme.png)
***Описание таблиц***:
1. **Vacancies** - таблица хранит в себе данные по вакансиям.  
2. **Areas** - таблица-справочник, которая хранит код города и его название.  
3. **Employers** - таблица-справочник со списком работодателей.  
4. **Industries** - таблица-справочник вариантов сфер деятельности работодателей.
5. **Employers_industries** - дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.

### Этапы работы над проектом
1. **Предварительный анализ данных**: подключение к базе, получение общей информации о структуре и количестве данных в каждой таблице.  
2. **Детальный анализ вакансий**: анализ предоставленных данных о вакансиях, подсчет статистических характеристик, выявление соответствия ожидаемым результатам.   
3. **Детальный анализ работодателей**: анализ предоставленных данных о работодателях, подсчет статистических характеристик, выявление соответствия ожидаемым результатам.    
4. **Предметный анализ**: анализ данных и подсчет статистических показателей для вакансий, имеющих отношение к Data Science.

### Результат  
Результаты анализа доступны в [`ноутбуке`](https://github.com/avfawkes/SF-DST_3.0/blob/main/Project2_SQL/Project_2_fin.ipynb).
