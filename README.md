## Отправить в GitHub:

`$ git add .` - Теперь Git отслеживает изменения в проекте,
добавление содержимого в индекс

`git restore --staged "файл..."` - Убрать из индекса
или
`git rm --cached "файл..."`

`git rm -f "файл..."` - принудительное удаление

`$ git commit -m "Text of the commit"` - Запись изменений в репозиторий

`$ git push origin master`

`git push -u origin master` - Git запоминает, что по умолчанию пушить будет в данную ветку и теперь пушить можно более коротко "git push"

`git push --dry-run` - проверка, удастся ли пушинг

`git remote add origin "ссылка на новый созданный проект в GitHub"` - Связывание локального Git с GitHub

## Скачать с GitHub в первый раз:

`$ git clone "Ссылка проекта..."`

## Получить обновления из репозитория:

`git pull origin master`

## Видимость репозитория:

`.gitignore` - раздел куда вносятся каталоги и файлы, которые будут видны локально

## Вывод состояния рабочего каталога:

`git status` - способ узнать про незапушенные коммиты

`git log` - более подробная информация про коммиты

## Базовые возможности и список команд GIT:

`git --help`

## Очистить консоль:

`clear`

## Список текущих директорий:

`dir`

## Переход и выбор директорий:

`cd "нужная директория"/`

## Возвращение на уровень назад:

`cd ..`

## Работа с каталогами:

`rm rf "наименование каталога"` - удаление католога без запроса

`mkdir "наименование создаваемого каталога"` - создание каталога

## Переинициализация нового или существующего репозитория:

`git init`

## Ветки; создание, удаление и т.д.:

`git branch` - вывод списка
`git branch "наименование"` - создание ветки
`git branch -D "наименование ветки"` - удаление ветки
`git checkout "наименование ветки"` - переключение между ветками
`git checkout -b "наменование ветки"` - создание новой ветки и переключение на неё
`git merge "наименование ветки"` - Объединение веток(находясь в основной ветке)