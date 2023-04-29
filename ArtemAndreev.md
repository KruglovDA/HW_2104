# Руководство
## Настройка Git
+ git config --global user.name "Your Name" - запись имени пользователя
+ git config --global user.email "your_email@whatever.com" - запись электронной почты пользователя
### Команды настройки сокращенного вида часто используемых команд
+ git config --global alias.co checkout
+ git config --global alias.ci commit
+ git config --global alias.st status
+ git config --global alias.br branch
+ git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"
## Команды инициализации и записи изменений
+ git init - инициализация репозитория
+ git add name file - добавить файл к коммиту
+ git add . - добавить к отслеживанию все файлы
+ git commit -m "comment" - записать изменения
+ git commit -am - коммит с одновременным добавлением всех изменений
+ git tag v1 - добавление тегов
+ git revert HEAD - отмена нежелательного коммита
## Дополнительные команды
+ git log - история коммитов
+ git log --all - просмотр полной истории
+ git log --graph - графическое представление структуры репозитория
+ git log --oneline - упрощенное представление структуры репозитория
+ git help command - помощь по команде
+ git diff - просмотр вносимых изменений
+ git status - просмотр состояния репозитория
## Работа с удаленным репозиторием
+ git remote - связь с удаленным репозиторием
+ git remote -v проверка связи
+ git push - отправка в удаленный репозиторий
+ git clone - получение удаленного репозитория
+ git fetch - получение изменений из удаленного репозитория
+ git pull - получение изменений из удаленного репозитория со слиянием
## Работа с ветками
+ git checkout - перемещение между узлами репозитория
+ git branch - создание новой ветки
+ git merge name branch - слияние веток
+ git checout - b name branch - создание новой ветки с одновременным переключением на нее
+ git branch -d name branch - удаление слитой веткио
## Полезные ссылки
+ [Курс по Git](https://vimeo.com/showcase/5616060)
