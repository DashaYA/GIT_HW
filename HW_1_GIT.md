GIT Homework 1

Для выполнения задания у вас должен быть установлен для Windows - GitBash.
Создан аккаунт в GitHub

Все шаги сценария выполняйте в терминале GitBush, Terminal, в папке под гитом.

Как отправить ДЗ на проверку.
 1. Создайте текстоовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash

Файл со сценарием и ссылку на свой гит хаб.

JSON
 4. Создать внешний репозиторий c названием JSON. 
github.com -> repositories -> New -> Repository name JSON -> Add a README file -> Create repository
 5. Клонировать репозиторий JSON на локальный компьютер.
git clone https://github.com/DashaYA/JSON.git
ls -la
появилась папочка скаченный Github репозиторий
 6. Внутри локального JSON создать файл “new.json”.
зайти cd json
создать touch new.json
проверить ls -la
 7. Добавить файл под гит. 
git add new.json
проверяем git status
 8. Закоммитить файл.
git commit -m "JSON1"
 9. Отправить файл на внешний GitHub репозиторий.
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). 
Всё написать в формате JSON.
заходим в редактов
vim new.json
нажимаем i и пишем там:
{
        "FIO":"Yakimenok Daria Sergeevna",
        "AGE": 35,
        "ANIMAL": 0,
        "SALARY": 1000
}
зажимаем ESC и пишем :wq (сохранить и выйти) Enter
git commit -a -m "JSON1"

 11. Отправить изменения на внешний репозиторий.
git push

 12. Создать файл preferences.json
cat > preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
touch preferences.json
vim preferences.json

{
        "movie": "Forrest Gump",
        "series": "Wednesday",
        "food": "delicious",
        "country": "Cyprus"
}

14. Создать файл sklls.json добавить информацию о скиллах 
которые будут изучены на курсе в формате JSON
touch skills.json
vim skills.json

nano skills.txt
{
	"skills":[
		"1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.",
		"2. Что такое клиент-серверная архитектура.",
		"3. HTTP Методы запросов на сервер.",
		"4. Коды ответов HTTP сервера.",
		"5. Структуры HTTP запросов и ответов.",
		"6. Что такое JSON, XML. Их структура.",
		"7. Тестирование API через Postman (JS, автотесты API).",
		"8. Снятие и чтение логов c внешнего сервера.",
		"9. Снифинг http web трафика через Charles и Fiddler.",
		"10. Dev Tools веб браузеров (Google Chrome, FireFox).",
		"11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
		"12. Мобильное тестирование.",
		"13. Особенность iOS, Android, гайдлайны.",
		"14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
		"15. Сборка Android приложений на Android Studio.",
		"16. ADB (управление андройд девайсами).",
		"17. Настройка прокси и vpn на iOS и Android.",
		"18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.",
		"19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
		"20. Основы bash скриптинг, автоматизация рутинных задач на сервере.",
		"21. Доступ к удалённым серверам.",
		"22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
		"23. База данных Postgres (установка, настройка и использование).",
		"24. Нереляционная база данных Redis (установка, настройка и использование).",
		"25. Нагрузочное тестирование в Jmeter.",
		"26. Методология разработки Scrum.",
		"27. Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы)",
		"28. Python. (Изучение основ. Создание клиент серверного приложения)"
	]
}



 15. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit -m "skills and preferences.json "
git push
 16. На веб интерфейсе создать файл bug_report.json.
repositories -> JSON -> Add file -> Create new file -> name new file -> bug_report.json -> Commit changes
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
JSON -> bug_report.json -> Edit this file
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 20. Синхронизировать внешний и локальный репозиторий JSON
git pull

XML
 21. Создать внешний репозиторий c названием XML.
github.com -> repositories -> New -> Repository name XML-> Add a README file -> Create repository
 22. Клонировать репозиторий XML на локальный компьютер.
создать папку, зайти туда
клонировать git clone https://github.com/DashaYA/XML.git
зайти в папку XML чтобы отразилось (main)

 23. Внутри локального XML создать файл “new.xml”.
touch new.xml
проверяем ls -la
 24. Добавить файл под гит.
git add new.xml
проверяем git status стало зеленым+

 25. Закоммитить файл.
git commit -m "xml"
 26. Отправить файл на внешний GitHub репозиторий.
git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). 
Всё написать в формате XML.
vim new.xml
нажать i
<?xml version="1.0" encoding="windows-1251"?>
<info>
	<full name>Yakimenok Daria Sergeevna</full name>
	<age>35</age>
	<count home pets>0</count home pets>
	<salary>1000</salary>
</info>
нажать Shift :wq Enter

 28. Отправить изменения на внешний репозиторий.
git commit -am "info in new.xml"

 29. Создать файл preferences.xml
touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) 
в формате XML.
vim preferences.xml
i
<?xml version="1.0" encoding="windows-1251"?>
<info>
        <film>Forrest Gump</film>
        <serial>Wednesday</serial>
        <food>delicious</food>
        <season>Summer</season>
        <side of the world>Cyprus</side of the world>
</info>

Esc
Shift :wq Enter

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
touch sklls.xml
vim sklls.xml
i 

<?xml version="1.0" encoding="windows-1251">
<skills>
                <skill-1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.)</skill-1>
                <skill-2>Что такое клиент-серверная архитектура.</skill-2>
                <skill-3>HTTP Методы запросов на сервер.</skill-3>
                <skill-4>Коды ответов HTTP сервера.</skill-4>
                <skill-5>Структуры HTTP запросов и ответов.</skill-5>
                <skill-6>Что такое JSON, XML. Их структура.</skill-6>
                <skill-7>Тестирование API через Postman (JS, автотесты API).</skill-7>
                <skill-8>Снятие и чтение логов c внешнего сервера.</skill-8>
                <skill-9>Снифинг http web трафика через Charles и Fiddler.</skill-9>
                <skill-10>Dev Tools веб браузеров (Google Chrome, FireFox).</skill-10>
                <skill-11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</skill-11>
                <skill-12>Мобильное тестирование.</skill-12>
                <skill-13>Особенность iOS, Android, гайдлайны.</skill-13>
                <skill-14>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</skill-14>
                <skill-15>Сборка Android приложений на Android Studio.</skill-15>
                <skill-16>ADB (управление андройд девайсами).</skill-16>
                <skill-17Настройка прокси и vpn на iOS и Android.</skill-17>
                <skill-18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</skill-18>
                <skill-19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса</skill-19>
                <skill-20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</skill-20>
                <skill-21>Доступ к удалённым серверам.</skill-21>
                <skill-22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</skill-22>
                <skill-23>База данных Postgres (установка, настройка и использование).</skill-23>
                <skill-24>Нереляционная база данных Redis (установка, настройка и использование).</skill-24>
                <skill-25>Нагрузочное тестирование в Jmeter.</skill-25>
                <skill-26>Методология разработки Scrum.</skill-26>
                <skill-27>Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный)</skill-27>
                <skill-28>Python. (Изучение основ. Создание клиент серверного приложения)</skill-28>
</skills>

Esc
Shift+:wq+Enter

 32. Сделать коммит в одну строку.
git add . && git commit -m "comment"
 33. Отправить сразу 2 файла на внешний репозиторий.
git push
 34. На веб интерфейсе создать файл bug_report.xml.
Add file -> Create new file -> Name: bug_report.xml
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit New File
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
XML -> bug_report.xml -> Edit this file
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 38. Синхронизировать внешний и локальный репозиторий XML
git pull

TXT
 1. Создать внешний репозиторий c названием TXT.
github.com -> repositories -> New -> Repository name TXT -> Add a README file -> Create repository
 2. Клонировать репозиторий TXT на локальный компьютер.
git clone https://github.com/DashaYA/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
cd TXT
touch new.txt
 4. Добавить файл под гит.
git add new.txt
 5. Закоммитить файл.
git commit -m "new.txt"
 6. Отправить файл на внешний GitHub репозиторий.
git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). 
Всё написать в формате TXT.
vim new.txt
full name: Yakimenok Daria Sergeevna
age: 35
count home pets: 0
salary:1000 

 8. Отправить изменения на внешний репозиторий.
git add .
git commit -m "info in new.txt"
git push

или можно git commit -am "info in file new.txt" && git push

 9. Создать файл preferences.txt
touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
vim preferences.txt

film: Forrest Gump
serial: Wednesday
food: delicious
season: Summer
side of the world: Cyprus

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
touch sklls.txt
vim sklls.txt
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы)
28. Python. (Изучение основ. Создание клиент серверного приложения)

 12. Сделать коммит в одну строку.
git add . && git commit -m "comment"
 13. Отправить сразу 2 файла на внешний репозиторий.
git push
 14. На веб интерфейсе создать файл bug_report.txt.
repositories -> TXT -> Add file -> Create new file -> name new file -> bug_report.txt -> Commit changes
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
TXT -> bug_report.txt -> Edit this file
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
id - PR1-B1
Summary - Кнопка “Оформить заказ” не реагирует на клик на странице оформления заказа.
Project - Web site shop.com
Version - 1.1
Severity - Blocker
Priority - ASAP
Status - Open
Author - Vysotskiy S
Assigned To - Ivanov I
Description:
  Precondition:
    1 - Зарегистрироваться на сайте shop.com
    2 - Авторизоваться на сайте
  Environment - MacOS BigSur v:11.2.3. Google Chrome v: 94.0.4606.71 (x86_64)
  Steps_to_reproduce:
    1 - Добавить товар в корзину
    2 - Зайти в корзину
    3 - Нажать на кнопку оформить заказ
  Actual_result - Кнопка “Оформить заказ” не реагирует на клик.
  Expected result - Пользователь перенаправляется на страницу оплаты (Биллинг)
Attachment - https://drive.google.com/...
 18. Синхронизировать внешний и локальный репозиторий TXT
git pull
