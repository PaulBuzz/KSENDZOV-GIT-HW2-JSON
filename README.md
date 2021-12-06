# JSON
**JSON Rep for HW2 @ Ksendzov Course**

1. Создайте текстоовый файл как в первом ДЗ по Terminal.
2. Сценарий перенесите в этот файл.
3. Напротив каждого действия - напишите команду в GitBash.
- Command: cd /Users/macintosh/Desktop/CODING/KSENDZOV/HW2
- Перемещаемся в папку, куда будем клонировать репозиторий, который мы только что создали.
4. Создать внешний репозиторий c названием JSON. 
- ![Creating Repository 1](https://www.dropbox.com/s/yk6goz9o5nntofj/JSON01.svg?dl=0)
- ![Creating Repository 2](https://www.dropbox.com/s/8swonmjpzw962ir/JSON02.svg?dl=0)
5. Клонировать репозиторий JSON на локальный компьютер.
- Command: git clone https://github.com/PaulBuzz/JSON
- Result: Клонирование в «JSON»…
- remote: Enumerating objects: 3, done.
- remote: Counting objects: 100% (3/3), done.
- remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
6. Внутри локального JSON создать файл “new.json”.
- Command: cd JSON
- Command: touch new.json
7. Добавить файл под гит.
- Command: git add “new.json”
8. Закоммитить файл.
- Command: git commit -m “commiting JSON to our rep”
9. Отправить файл на внешний GitHub репозиторий.
- Command: git push
10. Отредактировать содержание файла “new.json” – написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
- Command: vim new.json
- {
-    "NSF": {"name": "Pavel",
-    "surname": "Buzin",
-    "father_name": "Aleksandr"},
-    "age": 29,
-    "pets": 0,
-    "desired_salary": 6000
- }
11. Отправить изменения на внешний репозиторий.
- Command: git push
- Result: Перечисление объектов: 5, готово.
- Подсчет объектов: 100% (5/5), готово.
- При сжатии изменений используется до 8 потоков
- Сжатие объектов: 100% (3/3), готово.
- Запись объектов: 100% (3/3), 394 байта | 394.00 КиБ/с, готово.
Всего 3 (изменений 0), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
To https://github.com/PaulBuzz/JSON
12. Создать файл preferences.json.
- Command: touch preferences.json
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
- Command: vim preferences.json
- {
-    "fav_movie": "25th_hour",
-    "fav_TVSHOW": "Scrubs",
-    "fav_food": "Kebab",
-    "fav_season": "Autumn",
-    "country_to_visit": "Denmark"
- }
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.
- Command: skills.json
- Command: vim skills.json
- {
-    "skill_1": "HTTP",
-    "skill_2": "GIT",
-    "skill_3": "VPN",
-    "skill_4": "SQL",
-    "skill_5": "Postman",
-    "skill_6": "Charles",
-    "skill_7": "Fiddler",
-    "skill_8": "Android_Studio",
-    "skill_9": "XCODE",
-    "skill_10": "QA_Theory"
- }
15. Отправить сразу 2 файла на внешний репозиторий.
- Command: git add .
- Command: git commit preferences.json skills.json -m “adding two files to the rep”
- Result: [main 13ad22a] adding commits to 2 files
- 2 files changed, 19 insertions(+)
- create mode 100644 preferences.json
- create mode 100644 skills.json
- Command: git push
- Result:
- Перечисление объектов: 5, готово.
- Подсчет объектов: 100% (5/5), готово.
- При сжатии изменений используется до 8 потоков
- Сжатие объектов: 100% (4/4), готово.
- Запись объектов: 100% (4/4), 596 байтов | 596.00 КиБ/с, готово.
- Всего 4 (изменений 0), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
- To https://github.com/PaulBuzz/JSON
16. На веб интерфейсе создать файл bug_report.json.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
20. Синхронизировать внешний и локальный репозиторий JSON.
- Command: git pull
