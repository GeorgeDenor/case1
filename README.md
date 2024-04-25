# Краткий курс по Git
## Что такое Git?
Git - система управления версиями, используемая разработчиками для контроля за изменениями в проекте. Она особенно хорошо себя показывает при командной разработке. При командной разработке она часто используется соместно с системами управления удалёнными репозиториями вроде GitHUB и GitLab.


## Что нужно для Git?
### Установка Git
Для использования Git вам следует сперва его установить. Если вы пользователь Windows, то установите консольный инструмент [Git Bash](https://git-scm.com/download/win). Это терминал, который имеет схожий с Unix системами синтаксис команд. Так вам будет удобнее в дальнейшем использовать Git на любой системе. Терминал можно интегрировать в редактор VsCode.  
В случае, если вы используете Linux, перейдите на [официальный сайт Git](https://git-scm.com/download/linux) и выберите команду установки для своей версии Linux. Скопируйте её в программу Terminal и нажмите Enter. Введите в терминал команду для проверки.
```
$ git version
```
На macOS установите менеджер пакетов [Homebrew](https://brew.sh/).На сайте есть команда для установки. Введите в терминал команду
```
$ brew install git
```
Проверьте установку командой
```
$ git version
```

### Работа с терминалом
Далее вам понадобятся некоторые первичные навыки работы с терминалом.
Вот шпаргалка по базовым командам.
#### Навигация  
* ```pwd``` - (print work directory) показывает, в какой директории вы находитесь;  
* ```ls <dir>``` - (list direcry contents) показывает, какие файлы и папки находятся в папке ```dir```, или в текущей папке, если поле ```dir``` пустое;   
* ```ls -a <dir>``` - работает аналогично предыдущей команде, но ключ ```-a``` позволяет посмореть скрыте паки и файлы (их имена начинаются с .);   
* ```cd <dir>``` - (change directory) переводит вас в папку ```dir```.  
#### Работа с файлами и папками
##### Создание
* ```touch <file name>``` - создаёт файл с именем ```file name``` в текущей дирректории или в пути, указанном в имени файла;   
* ```mkdir <dir name>``` - (make directory) создаёт папку с именем ```dir name``` в текущей директории или в пути, указанном в названии дирректории.   
##### Копирование и преемещение
* ```cp <file> <dir>``` - (copy) копирует файл ```file```  в папку ```dir```;  
* ```mv <file> <dir>``` - (move) переносит файл ```file``` в папку ```dir```;  
#### Чтение файла
* ```cat <file>``` - (con**cat**enate and print) показывает содержимое файла ```file```, но работает только с тектовыми файлами.  
#### Удаление
* ```rm <file>``` - (remove) удаляет файл ```file``` безвозвратно (без перемещения в корзину); 
* ```rmdir <dir>``` - (remove directory) удаляет директорию ```dir``` безвозвратно, но работает только с пустыми папками; 
* ```rm -r <dir>``` - (**r** - recursive) удаляет все файлы и папки в директории ```dir``` безвозвратно.  



