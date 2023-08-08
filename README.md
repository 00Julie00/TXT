# Homework TXT for Git @ Vadim Ksendzov's Course
## GIT Homework 1

 **1. Создать внешний репозиторий c названием TXT**
 - создаю на своем github.com репозиторий с названием TXT
   
 **2. Клонировать репозиторий TXT на локальный компьютер**
 - `git clone https://github.com/00Julie00/TXT`

 **3. Внутри локального TXT создать файл “new.txt”**
 - перехожу в локальный репозиторий TXT
  `cd TXT` 
- создаю файл 
   `touch new.txt`

 **4. Добавить файл под гит**
- `git add -A`
- `git status`
 
 **5. Закоммитить файл**
- `git commit - m "add file new.txt";`
- `git push`

 **6. Отправить файл на внешний GitHub репозиторий**
- `git push`
 
 **7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT**

```
vim new.txt
i
name- Julia
surname- Ruanova
age- 39
pets- no
future_disired_salary- 600 $
ESC 
:wq
Enter
```
 
**8. Отправить изменения на внешний репозиторий**
- `git add -A` 
- `git status`
- `git commit -m "modified new.txt"` 
- `git push`
  
 **9. Создать файл preferences.txt**
- `touch preferences.txt`

 **10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT**
 ```
vim preferences.txt
i
favorite movie- Knockin 'on Heaven
favorite series- Game of Thrones
favorite food- bread
favorite season- summer
my future travel- Japan
ESC 
:wq
Enter
```
**11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**
```
vim sklls.txt
i
1) Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования, SDLC, STLC.
2) Основы клиент-серверная архитектура.
3) HTTP Методы запросов на сервер. Структуры HTTP запросов и ответов. Что такое JSON, XML. Их структура".
4) Тестирование API через Postman (JS, авто тесты API).
5) Снятие и чтение логов c внешнего сервера.
6) Снифинг http web трафика через Charles и Fiddler.
7) Dev Tools веб браузеров (Google Chrome, FireFox).
8) VPN. Как работает, зачем нужен, как использовать, варианты инструментов.
9) Мобильное тестирование.
10) Особенность iOS, Android, гайдлайны.
11) Сборка iOS приложений на XCode.
12) Сборка Android приложений на Android Studio.
13) ADB (управление андройд девайсами).
14) Настройка прокси и VPN на iOS и Android.
15) Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android".
16) Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса).
17) Основы bash скриптинг, автоматизация рутинных задач на сервере.
18) Доступ к удалённым серверам.
19) Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
20) База данных Postgres (установка, настройка и использование).
21) Нереляционная база данных Redis (установка, настройка и использование).
22) Нагрузочное тестирование в Jmeter.
23) Методология разработки Scrum.
24) Tехники тест-дизайна. Классы эквивалентности, граничные значения, комбинаторные техники (попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы.
ESC 
:wq
Enter
```
**12. Сделать коммит в одну строку**
- `git add -A && git commit -m "add preferences.txt, sklls.txt"`
  
**13. Отправить сразу 2 файла на внешний репозиторий**
- `git push`

**14. На веб интерфейсе создать файл bug_report.txt**
- создала файл на веб-интерфейсе файл с названием bug_report.txt
  
**15. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- сделала commit, сохранила изменения
  
**16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT**
- добавила изменения в файл
  
  ID - 506
Severity - Trivial
Environment- Samsung S20+ (Android 13), Big Sur 11.7.7
Title- [Cookies settings] link in the footer are not translated into local languages exept EN.
Steps:
     1) Navigate to capital.com
     1) Selected any languages except EN
     1) At the "Main Page" scroll down to the footer
Expected Result- [Cookies settings] link is translated into local languages.
Actual Result- [Cookies settings] link isn't translated into local languages.
Comments- The bug is also reproduced for the mobile.
Attachment- https://drive.google.com/julia/...

**17. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- сделала commit, сохранила изменения
 
**18. Синхронизировать внешний и локальный репозиторий TXT**
- получаю последнюю версию удаленного репозитория
`git pull`
