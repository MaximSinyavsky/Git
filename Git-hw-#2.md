# Git Homework №2
------------------------------------------------------------
1. На локальном репозитории сделать ветки для:

* Postman
* Jmeter
* CheckLists
* Bug_Reports
* SQL
* Charles
* Mobile_testing
------------------------------------------------------------
* перейти по ссылке https://github.com/
* нажать кнопку [NEW]
* в поле "Repository name" ввести "branch"
* отметить галочкой "Add a README file"
* нажать кнопку [Create repository]
* перейти по ссылке https://github.com/MaximSinyavsky/branch
* нажать кнопку [code]
* в вкладке SSH скопировать SSH-key
* в окне gitbush ввести:

		git clone git@github.com:MaximSinyavsky/branch.git
		git branch Postman; git branch Jmeter; git branch CheckLists; git branch Bug_Reports; git branch SQL; git branch Charles; git branch Mobile_testing
2. Запушить все ветки на внешний репозиторий

		git push -u origin --all
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

		git checkout Bag_Reports
		vim Bug_reports.txt
		-нажимаем "i"
			id
			title or summary
			Environment
			step to reproduce
			expected results
			actual results
			priority
			severity
			preconditions
			attachment
			reporter
			work around
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

4. Запушить структуру багрепорта на внешний репозиторий

		git add . && git commit -m "add bag reports structure"
		git push

5. Вмержить ветку Bag Reports в Main

		git checkout main
		git merge Bag_Reports

6. Запушить main на внешний репозиторий.

		git push

7. В ветке CheckLists набросать структуру чек листа.

		git checkout CheckLists
		vim CheckLists.txt
		 -нажимаем "i"
			-Версия  нашей  сборки  (Build,  билд).  Окружение  (Environment,  инвайранмент),  на  котором  проводилось тестирование. 
			-Дата проведения нашего теста. 
			-Тестировщик, который проводил данное тестирование.
			-Тип тестов, который был использован для тех или иных проверок. 
			-Название самих проверок. 
			-Результат нашего тестирования, т.е. прошла эта проверка или нет. 
		-нажимаем "esc", пишим ":wq", нажимаем "enter"

8. Запушить структуру на внешний репозиторий

		git add . && git commit -m "add checklists structure"
		git push 

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

* перейти по ссылке https://github.com/MaximSinyavsky/branch
* перейти во вкладку "Pull requests"
* нажать кнопку "New pull request"
* выбрать base:main, compare:CheckLists
* нажать кнопку "Create pull request"
* нажать кнопку "Create pull request"
* нажать кнопку "Merge pull request"
* нажать кнопку "Confirm merge"

10. Синхронизировать Внешнюю и Локальную ветки Main
		
		git fetch
		git pull
