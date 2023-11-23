# 13_2
### Домашнее задание к занятию «Защита хоста» - "Сергей Шульга"

### Задание 1

Установите eCryptfs.
 
sudo apt install ecryptfs-utils

Добавьте пользователя cryptouser.

adduser cryptouser

Зашифруйте домашний каталог пользователя с помощью eCryptfs.

Скрипт-обёртка ecryptfs-migrate-home создаст зашифрованный домашний каталог для пользователя и позаботится о переносе всех существующих файлов из ещё не зашифрованного домашнего каталога.

Для его запуска пользователь должен выйти из системы и не оставить никаких запущенных от его имени процессов. Лучший способ добиться этого — выйти из системы, войти в консоль как root и проверить, что команда ps -U cryptouser ничего не выводит. Также убедитесь, что у вас установлены rsync, lsof и which. После того как все необходимые условия выполнены, выполните:

modprobe ecryptfs
ecryptfs-migrate-home -u cryptouser



В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

### Задание 2

Установите поддержку LUKS.

Создайте небольшой раздел, например, 100 Мб.

Зашифруйте созданный раздел с помощью LUKS.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

### Задание 3 *

Установите apparmor.

Повторите эксперимент, указанный в лекции.

Отключите (удалите) apparmor.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.
