# Git Homework №1

## JSON

4. Создать внешний репозиторий c названием JSON.

* перейти по ссылке https://github.com/
* нажать кнопку [NEW]
* в поле "Repository name" ввести "JSON"
* отметить галочкой "Add a README file"
* нажать кнопку [Create repository]
5. Клонировать репозиторий JSON на локальный компьютер.

* перейти по ссылке https://github.com/MaximSinyavsky/JSON
* нажать кнопку [code]
* -в вкладке https скопировать URL
* в окне gitbush ввести:

		git clone https://github.com/MaximSinyavsky/JSON.git
6. Внутри локального JSON создать файл “new.json”.

		> new.json
7. Добавить файл под гит.

		git add new.json
8. Закоммитить файл.

		git commit -m "add new.json"
9. Отправить файл на внешний GitHub репозиторий.

		git push
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

		vim new.json
		-нажимаем "i"
		{
		"Name": "Maxim",
		"Age": "30",
		"Amount_pets": "1",
		"Desired_salary": "1000$"
		}
		-нажимаем "esc", пишим ":wq", нажимаем "enter"
11. Отправить изменения на внешний репозиторий.

		git commit -am "update new.json"
		git push
12. Создать файл preferences.json

		> preferences.json
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

		vim preferences.json
		-нажимаем "i"
		{
		"Muvie": "Avengers",
		"Series": "Supernatural",
		"Food": "Meat",
		"Season": "Summer",
		"Country": "Italy"
		}
		-нажимаем "esc", пишим ":wq", нажимаем "enter"
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

		vim skills.json
		-нажимаем "i"
			 		{
				    "Skills_1": "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC",
				    "Skills_2": "Что такое клиент-серверная архитектура",
				    "Skills_3": "HTTP Методы запросов на сервер",
				    "Skills_4": "Коды ответов HTTP сервера",
				    "Skills_5": "Структуры HTTP запросов и ответов",
				    "Skills_6": "Что такое JSON, XML. Их структура",
				    "Skills_7": "Тестирование API через Postman (JS, автотесты API)",
				    "Skills_8": "Снятие и чтение логов c внешнего сервера",
				    "Skills_9": "Снифинг http web трафика через Charles и Fiddler",
				    "Skills_10": "Dev Tools веб браузеров (Google Chrome, FireFox)",
				    "Skills_11": "Мобильное тестирование",
				    "Skills_12": "Особенность iOS, Android, гайдлайны",
				    "Skills_13": "Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
				    "Skills_14": "Сборка Android приложений на Android Studio.",
				    "Skills_15": "ADB (управление андройд девайсами)",
				    "Skills_16": "Настройка прокси и vpn на iOS и Android",
				    "Skills_17": "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
				    "Skills_18": "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
				    "Skills_19": "Основы bash скриптинг, автоматизация рутинных задач на сервере",
				    "Skills_20": "Доступ к удалённым серверам",
				    "Skills_21": "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
				    "Skills_22": "База данных Postgres (установка, настройка и использование)",
				    "Skills_23": "Нереляционная база данных Redis (установка, настройка и использование)",
				    "Skills_24": "Нагрузочное тестирование в Jmeter",
				    "Skills_25": "Методология разработки Scrum",
				    "Skills_26": "Python. (Изучение основ. Создание клиент серверного приложения)"
					}
		-нажимаем "esc", пишим ":wq", нажимаем "enter"
 
15. Отправить сразу 2 файла на внешний репозиторий.

		git add .
		git commit -m "add preferences and skills"
		git push

16. На веб интерфейсе создать файл bug_report.json.

* перейти по ссылке https://github.com/MaximSinyavsky/JSON
* нажать кнопку [add file]
* из развернувшегося списка выбрать "Create new file"
* в поле "name your file..." ввести bug_report.json

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

* в поле "Commit new file" ввести "create new file"
* нажать кнопку [Commit new file]

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

* перейти по ссылке https://github.com/MaximSinyavsky/JSON/blob/main/bug_report.json
* нажать кнопу [Edit this file]

		{
		"ID":"1",
		"title":"Не Работает кнопка оплаты",
		"step to reproduce":"пройти по ссылке..., добавить товар в корзину, перейти в корзину, нажать кнопку для оплаты....",
		"Environment":"Операционная система Win 10, browser Chrome 10.1",
		"expected result":"Прошла оплата",
		"actual result":"Ничего не происходит, деньги не снимаются",
		"Reporter":"Синявский Максим",
		"severity":"Blocker",
		"priority":"High",
		"attachment":"Прикрепленные скриншоты"
		}

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

* в поле "Commit new file" ввести "update new file"
* нажать кнопку [Commit new file]

20. Синхронизировать внешний и локальный репозиторий JSON

		git fetch
		git pull
	
## XML

21. Создать внешний репозиторий c названием XML.

* перейти по ссылке https://github.com/
* нажать кнопку [NEW]
* в поле "Repository name" ввести "XML"
* отметить галочкой "Add a README file"
* нажать кнопку [Create repository]

22. Клонировать репозиторий XML на локальный компьютер.

* перейти по ссылке https://github.com/MaximSinyavsky/XML
* нажать кнопку [code]
* в вкладке https скопировать URL
* в окне gitbush ввести:

		git clone https://github.com/MaximSinyavsky/XML.git

23. Внутри локального XML создать файл “new.xml”.

		> new.xml
24. Добавить файл под гит.

		git add new.xml
25. Закоммитить файл.

		git commit -m "add new.xml"	
26. Отправить файл на внешний GitHub репозиторий.

		git push
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

		vim new.xml
		-нажимаем "i"
		<?xml version="1.0" encoding="UTF-8"?>
			<new>
				<name>My name is Maxim.</name>
				<age>I am 30 years old.</age> 
				<pet>I have one pet.</pet> 
				<salary>Desired salary is 1000$.</salary>
			</new>
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

28. Отправить изменения на внешний репозиторий.

		git commit -am "update new.xml"
		git push

29. Создать файл preferences.xml

		> preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

		vim preferences.json
		-нажимаем "i"
		<?xml version="1.0" encoding="UTF-8"?>	
			 	<preferences>
					<muvie>My favorite movie is Avengers.</muvie>
					<series>My favorite series is Supernatural.</series> 
					<food>My favorite food is meat.</food> 
					<season>My favorite time of year is summer.</season> 
					<country>I want to visit Italy.</country>
				</preferences>
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

		vim skills.json
		-нажимаем "i"
			<?xml version="1.0" encoding="UTF-8"?>
			<skills> 
				<title>В рамках данного курса будут изучены:</title>
					<skills1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.</skills1>
					<skills2>Что такое клиент-серверная архитектура</skills2>
					<skills3>HTTP Методы запросов на сервер</skills3>
					<skills4>Коды ответов HTTP сервера.</skills4>
					<skills5>Структуры HTTP запросов и ответов.</skills5>
					<skills6>Что такое JSON, XML. Их структура.</skills6>
					<skills7>Тестирование API через Postman (JS, автотесты API).</skills7>
					<skills8>Снятие и чтение логов с внешнего сервера.</skills8>
					<skills9>Сниффинг http web трафика через Charles и Fiddler.</skills9>
					<skills10>Dev Tools веб браузеров (Google Chrome, FireFox).</skills10>
					<skills11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</skills11>
					<skills12>Мобильное тестирование.</skills12>
					<skills13>Особенность iOS, Android, гайдлайны.</skills13>
					<skills14>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</skills14>
					<skills15>Сборка Android приложений на Android Studio.</skills15>
					<skills16>ADB (управление андроид девайсами).</skills16>
					<skills17>Настройка прокси и vpn на iOS и Android.</skills17>
					<skills18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</skills18>
					<skills19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</skills19>
					<skills20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</skills20>
					<skills21>Доступ к удалённым серверам.</skills21>
					<skills22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</skills22>
					<skills23>База данных Postgres (установка, настройка и использование).</skills23>
					<skills24>Нереляционная база данных Redis (установка, настройка и использование).</skills24>
					<skills25>Нагрузочное тестирование в Jmeter.</skills25>
					<skills26>Методология разработки Scrum.</skills26>
					<skills27>Python. (Изучение основ. Создание клиент серверного приложения)</skills27>
			</skills>
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

32. Сделать коммит в одну строку.

		git add . && git commit -m "add preferences and skills xml"

33. Отправить сразу 2 файла на внешний репозиторий.

		git push
34. На веб интерфейсе создать файл bug_report.xml.

* перейти по ссылке https://github.com/MaximSinyavsky/XML
* нажать кнопку [add file]
* из развернувшегося списка выбрать "Create new file"
* в поле "name your file..." ввести bug_report.xml

35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

* в поле "Commit new file" ввести "create new file"
* нажать кнопку [Commit new file]

36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

* перейти по ссылке https://github.com/MaximSinyavsky/XML/blob/main/bug_report.xml
* нажать кнопу [Edit this file]

  		<?xml version="1.0" encoding="UTF-8"?>
		  <XML>
		    <id>1</id> 
		    <title or summary>Не работает кнопка оплаты</title or summary>
		    <environment>Операционная система Win 10, browser Chrome 10.1</environment>
		    <step to reproduce>пройти по ссылке..., добавить товар в корзину, перейти в корзину, нажать кнопку для оплаты....</step to reproduce>
		    <expected results>Прошла оплата</expected results>
		    <actual results>Ничего не происходит, деньги не списываются</actual results>
		    <priority>high</priority>
		    <severity>blocker</severity>
		    <attachment>скриншоты</attachment>
		    <work around>нет</work around>
		    <reporter>Синявский Максим</reporter>
		  </XML>

37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

* в поле "Commit new file" ввести "update new file"
* нажать кнопку [Commit new file]

38. Синхронизировать внешний и локальный репозиторий XML

		git fetch
		git pull

# TXT

 39. Создать внешний репозиторий c названием TXT.

* перейти по ссылке https://github.com/
* нажать кнопку [NEW]
* в поле "Repository name" ввести "TXT"
* отметить галочкой "Add a README file"
* нажать кнопку [Create repository]

40. Клонировать репозиторий TXT на локальный компьютер.

* перейти по ссылке https://github.com/MaximSinyavsky/TXT
* нажать кнопку [code]
* в вкладке https скопировать URL
* в окне gitbush ввести:

		git clone https://github.com/MaximSinyavsky/TXT.git

41. Внутри локального TXT создать файл “new.txt”.

		> new.txt
42. Добавить файл под гит.

		git add new.txt
43. Закоммитить файл.

		git commit -m "add new.txt"
44. Отправить файл на внешний GitHub репозиторий.

		git push

45. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

		vim new.json
		-нажимаем "i"
 		My name is Maxim. 
		I am 30 years old. 
		I have one pet. 
		My cat's name is Vegas. 
		Desired salary is 1000$.
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

46. Отправить изменения на внешний репозиторий.

		git commit -am "Update new.txt"
		git push

47. Создать файл preferences.txt

		> preferences.txt

48. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

		vim preferences.txt
		-нажимаем "i"
		My favorite movie is Avengers. 
		My favorite series is Supernatural. 
		My favorite food is meat. 
		My favorite time of year is summer. 
		I want to visit Italy.
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

49. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

		vim skills.txt
 		-нажимаем "i"
		 		В рамках данного курса будут изучены:
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
		27. Python. (Изучение основ. Создание клиент серверного приложения)
		-нажимаем "esc", пишим ":wq", нажимаем "enter"
 
50. Сделать коммит в одну строку.

		git add . && git commit -m "add preferences and skils txt"

51. Отправить сразу 2 файла на внешний репозиторий.

		git push

52. На веб интерфейсе создать файл bug_report.txt.

* перейти по ссылке https://github.com/MaximSinyavsky/TXT
* нажать кнопку [add file]
* из развернувшегося списка выбрать "Create new file"
* в поле "name your file..." ввести bug_report.txt

53. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* в поле "Commit new file" ввести "create new file"
* нажать кнопку [Commit new file]

54. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

* перейти по ссылке https://github.com/MaximSinyavsky/TXT/blob/main/bug_report.txt
* нажать кнопу [Edit this file]

  		id -1 
			titles or summary- Не работает кнопка оплаты
			environment- Операционная система Win 10, browser Chrome 10.1
			step to reproduce- пройти по ссылке..., добавить товар в корзину, перейти в корзину, нажать кнопку для оплаты....
			expected results-Прошла оплата
			actual results-Ничего не происходит, деньги не списываются 
			priority-high
			severity-blocker
			attachment-скриншоты
			work around-нет
			reporter-Максим

55. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

* в поле "Commit new file" ввести "update new file"
* нажать кнопку [Commit new file]

56. Синхронизировать внешний и локальный репозиторий TXT

		git fetch
		git pull
