# JSON
Homework

1. Создать внешний репозиторий c названием JSON.
	```
	 Repositories -> New -> "Repository name": Json -> Create repository
	```
2. Клонировать репозиторий JSON на локальный компьютер.
	```
	 git clone https://github.com/Lliniya/JSON.git
	```
3. Внутри локального JSON создать файл “new.json”.
	```
	 cd json
	 touch new.json
	```
4. Добавить файл под гит.
	```
	 git add new.json
	 git status
	```
5. Закоммитить файл.
	```
	 git commit -m "add first new.json file"
	```
6. Отправить файл на внешний GitHub репозиторий.
	```
	 git push
	```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
	```
	 {
	     "ФИО":"Корягина Алина Александровна",
	     "Возраст":"24",
	     "Домашние животные":null,
	     "Будущая желаемая зарплата":"3000$"
	 }
	```
8. Отправить изменения на внешний репозиторий.
	```
	 git status
	 git add new.json
	 git commit -m "edit the new.json file"
	 git push
	```
9. Создать файл preferences.json
	```
	 touch preferences.json
	```
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
	```
  	 {
	     "Любимый фильм":"Лучшее предложение",
	     "Любимый сериал":"Удивительная мисис Мэйзел",
	     "Любимая еда":"йогурты",
	     "Любимое время года":"лето",
	     "Страна,котоую хотела бы посетить":"Исландия"
	 }
	```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.
	```
	 touch sklls.json
	```
	Файл редактировал в Sublime Text:
	```
	 {
	     "Базовая теория": [
   		 "что такое тестирование",
   		 "багрепорты, документация",
   		 "виды, методы, направления тестирования и т.п.",
   		 "SDLC, STLC",
   		 "клиент-серверная архитектура",
   		 "HTTP Методы запросов на сервер"
   		 "коды ответов HTTP сервера"
   		 "структуры HTTP запросов и ответов"],
	     "JSON, XML":"что это такое, их структура",
	     "Тестирование API":"Postman (JS, автотесты API)",
	     "Снифинг": [
   		 "http web трафика через Charles и Fiddler",
   		 "мобильного трафика через Charles и Fiddler на iOS и Android"],
	     "Dev Tools веб браузеров":"Google Chrome, FireFox",
	     "VPN":"Как работает, зачем нужен, как использовать, варианты инструментов",
	     "Мобильное тестирование":[
    		 "особенность iOS, Android, гайдлайны",
    		 "сборка iOS приложений на XCode",
    		 "сборка Android приложений на Android Studio",
    		 "ADB (управление андройд девайсами)",
    		 "настройка прокси и vpn на iOS и Android"],
	     "Командная строка (terminal) Linux":[
    		 "копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса",
    		 "основы bash скриптинг, автоматизация рутинных задач на сервере"],
	     "Базы данных":[
    		 "основы SQL:Create, Delete, Drop, Insert Into, Select, From, Where, Join",
    		 "Postgres (установка, настройка и использование)",
    		 "Нереляционная база данных Redis (установка, настройка и использование)"],
	     "Нагрузочное тестирование":"Jmeter",
	     "Методологии разработки ПО":"Scrum, водопадная, итерационная, инкрементальная, спиральная, V-образная"
	 }
	```
12. Отправить сразу 2 файла на внешний репозиторий.
	```
	 git add preferences.json sklls.json
	 git commit -m "add preferences.json , sklls.json"
	 git push
	```
13. На веб интерфейсе создать файл bug_report.json.
	```
	 Repositories -> JSON -> Add file -> Create new file -> "Name your file": bug_report.json
	```
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	 Блок "Commit new file"
	 В поле заголовка: create bug_report.json
	 В поле описания: create my first bug_report.json
	 Нажать на кнопку "Commit changes"
	```
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	```
	 Repositories -> JSON -> bug_report.json -> Edit this file 
	 Приступить к редактированию файла в поле "Edit file"
	```
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	 Блок "Commit changes"
	 В поле заголовка: можно оставить пустым, а можно указать Update bug_report.json
	 В поле описания: "added first bug report"
	 Нажать на кнопку "Commit changes"
	```
17. Синхронизировать внешний и локальный репозиторий JSON.
	```
	 git pull
	```
