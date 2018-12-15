# my-web-klass-projects
## Инструменты
state edits

# Создание репозитория

### На сервере
### На сайте GitHub:

## На локальном компьютере
### Клонируем с GitHub
Клонирование репозитория осуществляется командой git clone [url]. Например, если вы хотите клонировать библиотеку Ruby Git, известную как Grit, вы можете сделать это следующим образом:

$ git clone git@github.com:vrazumov/my-web-klass-projects.git

Если вы хотите клонировать репозиторий в каталог, отличный от grit, можно это указать в следующем параметре командной строки:

$ git clone git@github.com:vrazumov/my-web-klass-projects.git new-web-klass-projects
Эта команда делает всё то же самое, что и предыдущая, только результирующий каталог будет назван mygrit.

### Создаем новый локально
mkdir my-project
cd my-project
git init

Эта команда создаёт в текущем каталоге новый подкаталог с именем .git содержащий все необходимые файлы репозитория — основу Git-репозитория.

Включаем файлы ( например *.c) под версионный контроль
$ git add *.c
$ git add README
$ git commit -m 'initial project version'

## Update GitHub repository
git push git@github.com:vrazumov/my-web-klass-projects.git


## Clone branch
git clone -b develop git@github.com:vrazumov/my-web-klass-projects.git

## Edited in Visual Studio Code

### Clones a repository to your computer
git clone git@github.com:vrazumov/my-web-klass-projects.git

### Добавление файлов
1. add текущие изменения
2. commit
3. push to git@github.com:vrazumov/my-web-klass-projects.git
4. push

Если у вас есть желание пропустить этап индексирования, Git предоставляет простой способ. Добавление параметра -a в команду git commit заставляет Git автоматически индексировать каждый уже отслеживаемый на момент коммита файл, позволяя вам обойтись без git add:

## Удаление файлов








