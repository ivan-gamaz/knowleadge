# Здеcь отражены мои знания по **GIT** и **GITHUB**

Начнём с команд для **GIT**

---


### pwd — выводит каталог, в котором мы работаем


### ls - выводит содержимое директории


Есть некоторые расширения для этой команды

- -l - выводит файлы списком
- -a - выводит все скрытые файлы.

cd - меняет деректорию 

###Так же если ввести `cd .` то мы перейдём на текущюю директорию, а если ввести  `cd ..` мы перейдём на директорию выше

### mkdir - создаёт новую директорию 


Есть некоторые расширения для этой команды
-p - можно создать каталог файлов.

### touch - Создаёт файлы

### cp - Копирует файл и вставляет в данную директорию

### mv - перемещает файл в данную директорию

### cat - читает файл

### rm/rmdir - удаляет файл/директорию.

#### есть некоторое расширение для rm это -r, чтобы удалять папки с файлами


```mermaid
graph LR; 
untraked -- "git add" --> staged;
staged -- "???"   --> tracked/comited;
```