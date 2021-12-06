# JSON
**JSON Rep for HW2 @ Ksendzov Course**

1. Создайте текстоовый файл как в первом ДЗ по Terminal.
2. Сценарий перенесите в этот файл.
3. Напротив каждого действия - напишите команду в GitBash.
- Command: cd /Users/macintosh/Desktop/CODING/KSENDZOV/HW2
- Перемещаемся в папку, куда будем клонировать репозиторий, который мы только что создали.
4. Создать внешний репозиторий c названием JSON. 
- <img width="1002" alt="JSON01" src="https://user-images.githubusercontent.com/84155505/144819547-5eb8e39e-026a-47ef-b2f5-14c4756bf5e4.png">
- <img width="747" alt="JSON02" src="https://user-images.githubusercontent.com/84155505/144819624-d26b071d-c661-4fdd-a167-9f03f53e444b.png">
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
- <img width="1010" alt="JSON03" src="https://user-images.githubusercontent.com/84155505/144821032-13b3e89a-bb67-4461-977b-a504353580df.png">
- <img width="1015" alt="JSON04" src="https://user-images.githubusercontent.com/84155505/144821067-d8619a34-9af1-4902-8fad-cb3164059f2a.png">
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- <img width="1300" alt="JSON05" src="https://user-images.githubusercontent.com/84155505/144821231-ef5daaab-3881-4b30-89a5-fe11689c0579.png">
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
- <img width="1336" alt="JSON06" src="https://user-images.githubusercontent.com/84155505/144821275-40f635fc-15f4-48eb-a710-9336d7e11429.png">
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- <img width="1361" alt="JSON07" src="https://user-images.githubusercontent.com/84155505/144821316-745aea94-915b-4e99-bb02-bac010920933.png">
20. Синхронизировать внешний и локальный репозиторий JSON.
- Command: git pull
