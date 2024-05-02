# помощник git

## начало

качаем git и bash 
```
https://git-scm.com/download/win
```
устанавливаем


## основные команды

pwd (от англ. print working directory, «показать рабочую папку») — покажи, в какой я папке;

ls (от англ. list directory contents, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;

ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа .;

cd first-project (от англ. change directory, «сменить директорию») — перейди в папку first-project;

cd first-project/html — перейди в папку html, которая находится в папке first-project;

cd .. — перейди на уровень выше, в родительскую папку;

cd ~ — перейди в домашнюю директорию (/Users/Username);

cd / — перейди в корневую директорию.

touch index.html (англ. touch, «коснуться») — создай файл index.html в текущей папке;

touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;

mkdir second-project (от англ. make directory, «создать директорию») — создай папку с именем second-project в текущей папке.

cp file.txt ~/my-dir (от англ. copy, «копировать») — скопируй файл в другое место;

mv file.txt ~/my-dir (от англ. move, «переместить») — перемести файл или папку в другое место.

cat file.txt (от англ. concatenate and print, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.

rm about.html (от англ. remove, «удалить») — удали файл about.html;

rmdir images (от англ. remove directory, «удалить директорию») — удали папку images;

rm -r second-project (от англ. remove, «удалить» + recursive, «рекурсивный») — удали папку second-project и всё, что она содержит.


## настройка git

$ git config --global user.name "User Namovich" 

имя или ник нужно написать латиницей и в кавычках

$ git config --global user.email username@yandex.ru

здесь нужно указать свой настоящий email 

$ git config --list 


## создание репозитория и иже с ним

$ cd ~/dev/first-project # перешли в нужную папку

$ git init # создали репозиторий 

проверить состояние репозитория — git status

подготовить файлы к сохранению — git add

$ git add --all # подготовили к сохранению все файлы в репозитории

$ git add . # добавить всю текущую папку

выполнить коммит — git commit

$ git commit -m 'Мой первый коммит!'

просмотреть историю коммитов — git log
