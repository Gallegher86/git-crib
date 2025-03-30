###Основная информация по командам Git и работе в GitHub

####Инициализация репозитория
___

* __git init (от англ. initialize, «инициализировать»)__ — *инициализируй репозиторий.*

####Подготовка файла к коммиту
___

* __git add todo.txt (от англ. add, «добавить»)__ — *подготовь файл todo.txt к коммиту.*
* __git add --all (от англ. add, «добавить» + all, «всё»)__ — *подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы.*
* __git add .__ — *подготовь к коммиту текущую папку и все файлы в ней.*

####Создание коммита
___

* __git commit -m "Комментарий к коммиту." (от англ. commit, «совершать», «фиксировать» + message, «сообщение»)__ — *сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены.* 

####Просмотр информации о коммитах
___

* __git log (от англ. log, «журнал [записей]»)__ — *выведи подробную историю коммитов.*

####Просмотр состояния файлов
___

* __git status (от англ. status, «статус», «состояние»)__ — *покажи текущее состояние репозитория.*

####Генерация SSH ключа
___

* __ssh-keygen -t rsa -b 4096 -C {ваш email}__ — *создает пару SSH ключей.*
* __clip < ~/.ssh/id_ed25519.pub__ — *скопировать содержимое SSH ключей в буфер обмена.*

####Связывание локального и удаленного репозитория
___
* __git remote add origin {ссылка на GitHub}__  — *связать локальный и удаленный репозиторий.*
* __git remote -v__  — *проверить связность репозиториев.*
* __git push -u origin main__ — *отправить изменения на удаленный репозиторий __в первый раз__* 
* __git push__ — *отправить изменения на удаленный репозиторий* 

####Копирование репозитория
* __git clone {URL репозитория на GitHub}__ — *клонировать проект с удаленного репозитория в локальный.* 