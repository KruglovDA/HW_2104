1. Создать репозиторий на GitHub вверху справа плюсик - New Repository

   Ввести Repository name -уникально для владельца

   Description - не обязательно

   Add file [Readme.md](http://Readme.md) - создаст файл

   Add .gitignore - папку для тей файлов которые не требуется добавлять для отслеживания

   Create…

2. Адрес сформированный вставляется при выполнении команды git clone ссылка

- Вариант первый - создает локальный репозиторий в выбранной папке
  ```
  echo "# seminar3" >> README.md - создает файл README.md с текстом заголовком seminar3
  git init - инициализирует репозиторий
  git add README.md - добавляет в отслеживаний созданный файл
  git commit -m "first commit" - создает коммит
  git branch -M main - переименовывает текущую вертку в main
  git remote add origin ссылка - связывает локальный репозиторий с удаленным
  git push -u origin main - наши изменения отправляет на удаленный репозиторий
  ```
- Второй вариант - это уже для готового репозитория, где до этого сделали уже инициализацию, add и commit
  ```
  git remote add origin ссылка
  git branch -M main
  git push -u origin main
  ```
