# 13_2
### Домашнее задание к занятию «Защита хоста» - "Сергей Шульга"

### Задание 1

Установите eCryptfs.
 
- sudo apt install ecryptfs-utils

Добавьте пользователя cryptouser.

- sudo adduser --encrypt-home cryptouser
  
![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/001.png)

Зашифруйте домашний каталог пользователя с помощью eCryptfs.

В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/002.png)


### Задание 2

Установите поддержку LUKS.

Создайте небольшой раздел, например, 100 Мб.

Зашифруйте созданный раздел с помощью LUKS.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/003.png)

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/004.png)

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/005.png)

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/006.png)

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/007.png)

![alt text](https://github.com/SergeiShulga/13_2/blob/main/img/008.png)

### Задание 3 *

Установите apparmor.

Повторите эксперимент, указанный в лекции.

Отключите (удалите) apparmor.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.
