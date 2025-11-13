1. Мой проект:
Сбор заголовков статей на сайте hubr.com
Habr Article Scraper

2. Проблема, для чего: 
Скрипт создан для автоматического сбора всех заголовков, ссылок и метаданных статей с главной страницы habr.com/ru/feed/

3. Используемые технологии:
Python 3.x, Requests, BeautifulSoup, Pandas (для экспорта).

4. Ключевые функции:
1) Обработка пагинации: Скрипт может пройти до N-страниц.
2) Обход защиты: Используется ротация заголовков User-Agent.
3) Чистый экспорт: Данные экспортируются в структурированный DataFrame и .xlsx файл.


5. Результат:
<img width="1376" height="583" alt="image" src="https://github.com/user-attachments/assets/c7dbc2ae-c017-4eb8-8a83-2aee8ca74944" />


7. Инструкция по запуску:
1) Клонируйте репозиторий: https://github.com/NikitaCARENYTENtetyntn/Habr-Scraper.git
2) Установите все зависимости: pip install -r requirements.txt
3) Запустите скрипт: python headers.py 
