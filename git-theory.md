## 1. Что такое Git?
Git — распределённая система контроля версий, которая даёт возможность разработчикам отслеживать изменения в файлах и работать совместно с другими разработчиками.
Подход Git к хранению данных больше похож на набор снимков миниатюрной файловой системы. При каждом сохранении состояния своего проекта в Git, система запоминает, как выглядит каждый файл в этот момент, и сохраняет ссылку на этот снимок.

## 2. Что такое ssh ключ? Как работает?
Ключ SSH — это криптографический безопасный идентификатор. Это похоже на действительно длинный пароль, используемый для идентификации вашей машины. GitHub использует ключи SSH, чтобы вы могли загружать файлы в репозиторий без необходимости каждый раз вводить свое имя пользователя и пароль.
Во-первых, нам нужно проверить, установлен ли у вас уже SSH-ключ. Введите это в терминал:
      
      ls ~/.ssh/id_rsa.pub
Если в консоли появляется сообщение с текстом «Нет такого файла или каталога», значит, у вас еще нет SSH-ключа, и вам нужно будет его создать. Если в выводе консоли не появилось никакого сообщения, значит, у вас уже есть ключ.
Чтобы создать новый ключ SSH, выполните следующую команду в своем терминале. Используйте программу ssh-keygen с флагом -C, за которым следует ваш адрес электронной почты, для чего введите:

    ssh-keygen -t rsa -b 4096 -C "ВАШ_EMAIL@mail.com"






## 3. Что такое git clone? Как работает?
## 4. Что такое git config? Как работает?
## 5. Ветвление в git: как и зачем использовать ветки?
## 6. Что такое git status? Как работает?
## 7. Что такое git add? Как работает?
## 8. Что такое git ignore? Как работает?
## 9. Что такое git commit? Как работает?
## 10. Что такое git push? Как работает?
## 11. Что такое git branch? Как работает?
## 12. Что такое merge? Как работает? Как решить конфликт через git hub и через terminal?
## 13. Что такое git revert? Как работает?
## 14. Что такое git restore? Как работает?
## 15. Что такое git pull? Как работает?
## 16. Что такое git fetch? Как работает?
## 17. Как удалить удаленный репозиторий через github и через terminal?
## 18. Что такое git cherry-pick? Как работает?
## 19. Что такое git reset? Как работает?
## 20. Что такое git log? Как работает?
## 21. Что такое git rebase? Как работает?
## 22. Что такое git remote? Как работает?