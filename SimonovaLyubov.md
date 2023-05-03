# GIT. Краткое Руководство
## Локальный репозиторий
0. git config ­­global user.name "Your name" 
    git config ­­global user.email your email - настройка git первоначальная
1. git init - инициализация репозитория
2. git commit - создание коммита

* git commit -m "some_string" - делает commit с добавлением комментария
* git commit -am "some_string" - добавляет изменения файла в репозиторий или сам файл и делает commit с комментарием
3. git add - добавляет файл в репозиторий

* git add name_file - добавляет файл или его изменения в репозиторий
* git add - добавляет файлы или их изменения в репозиторий, кроме указанных в gitignore
4. git log - отображает журнал

* git log - отображает видимый журнал этой ветки
* git log --graph - отображает журнал виде дерева
5. git diff - отображает изменения
6. git checkout - выбирает, куда перейти

* git checkout xxxx - переходит по коммитам ветки, где xxxx - первые 4ре цифры коммита
* git checkout branch_name - переходит на существующую ветку
7. git status - отображает изменения
8. git branch - создает, отображает и удаляет ветки

* git branch - показывает все ветки
* git branch name - создает ветку с именем name
* git branch -d name - удаляет уже слитую ветку с именем name, в которой нет никаких изменений
* git branch -D name удаляет ветку с именем name
9. git merge - сливает ветки

* git merge name - сливает в текущую ветку ветку с именем name
10. git clone - клонирование внешнего репозитория на ПК
11. git pull - скачать все из текущего репозитория и слить с нашей версией
12. git push - отправить нашу версию репозитория на внешний репозиторий

## pull request
* fork на github
* git clone своей версии репозитория
* git branch name_version
* git checkout name_version
* git commit -am "Добавили в версию"
* git push или ctrl+c ctrl+v то, что предложит git
* pull request на git
