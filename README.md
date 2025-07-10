# Домашнее задание к занятию  «Защита хоста» - Плеханов С.А.

### Задание 1

1. Установите **eCryptfs**.
2. Добавьте пользователя cryptouser.
3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.


*В качестве ответа  пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.*  

### Решение 1

<img src = "img/Screenshot_1_1.png" width=100%>

<img src = "img/Screenshot_1_2.png" width=100%>


### Задание 2

1. Установите поддержку **LUKS**.
2. Создайте небольшой раздел, например, 100 Мб.
3. Зашифруйте созданный раздел с помощью LUKS.

*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*

### Решение 2

````sh 
$ sudo apt install gparted 
````
<img src = "img/Screenshot_2_1.png" width=100%>

````sh
$ sudo apt-get install cryptsetup
````
<img src = "img/Screenshot_2_2.png" width=100%>

<img src = "img/Screenshot_2_3.png" width=100%>

<img src = "img/Screenshot_2_4.png" width=100%>

<img src = "img/Screenshot_2_5.png" width=100%>

<img src = "img/Screenshot_2_6.png" width=100%>

<img src = "img/Screenshot_2_7.png" width=100%>
