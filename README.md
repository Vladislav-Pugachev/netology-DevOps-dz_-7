### 1.
```
type cd
cd is a shell builtin
```
> На сколько я понял cd является встоенной потому что ее задача менять директорию в текущей оболочке, а внешине команды реализуются в дочерних оболочках.

### 2.

>grep <some_string> <some_file> -c

### 3.

> systemd(1)

### 4.

> ls >/dev/pts/1

### 5.

> less 1 >  2

### 6.

```
vagrant@vagrant:~$ tty
/dev/pts/0
vagrant@vagrant:~$ echo 'Hello' > /dev/tty1
```

### 7.

> bash 5>&1
>> Связали дескриптор stdout c дескриптором 5

> echo netology > /proc/$$/fd/5
> > Перенапрвали вывод в дескриптор 5 который является stdout

### 8.

> 3>&1 1>&2 2>&3  | grep 

### 9.

> выводит переменные окружения 

- env

### 10.

> cmdline
> > файл в котором записываются аргументы командной строки

>exe
> > содержит символическую ссылку где указан фактический путь к исполняемой команде

### 11.

> sse4_2



