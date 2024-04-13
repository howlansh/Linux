## Part 1. Установка ОС
* Вывод версии Ubuntu
* ![Вывод версии Ubuntu](./screenshots/img_1.png)

## Part 2. Создание пользователя
* Команда для создания пользователя
* ![Команда для создания пользователя](./screenshots/img_2.1.png)
* Вывод команды cat /etc/passwd
* ![Вывод команды cat /etc/passwd](./screenshots/img_2.2.png)

## Part 3. Настройка сети ОС
* Имя машины можно задать командой "hostnamectl set-hostname user-1"  или редактировать название в файле "/etc/hostname".
* ![](./screenshots/img_3.1.png)
* Для установки часового пояса сначала находим нужный часовой пояс командой "tzselect", затем выбираем его командой "timedatectl set-timezone Europe/Moscow".
* ![](./screenshots/img_3.2.png)
* Вывод названия сетевых интерфейсоф командой "ip link show".
* ![](./screenshots/img_3.3.png)
* lo (loopback device) – виртуальный интерфейс, присутствующий по умолчанию в любом Linux. Он используется для отладки сетевых программ и запуска серверных приложений на локальной машине. С этим интерфейсом всегда связан адрес 127.0.0.1. У него есть dns-имя – localhost. Посмотреть привязку можно в файле /etc/hosts.
* IP адресс от DHCP сервера.
* ![](./screenshots/img_3.4.png)
* DHCP — протокол прикладного уровня модели TCP/IP, служит для назначения IP-адреса клиенту. Это следует из его названия — Dynamic Host Configuration Protocol.
* Внешний и внутренний IP  адреса шлюза.
* ![](./screenshots/img_3.5.png)
* Открываем файл конфигурации сети.
* ![](./screenshots/img_3.6.png)
* Отключаем DHCP и прописываем IP адреса вручную.
* ![](./screenshots/img_3.7.png)
* Применение настроек и перезагрузка системы.
* ![](./screenshots/img_3.8.png)
* Проверка настроек.
* ![](./screenshots/img_3.9.png)
* Пинг удалённых хостов.
* ![](./screenshots/img_3.10.png)

## Part 4. Обновление ОС
* 
* ![](./screenshots/img_.png)

## Part 5. Использование команды  sudo
* 
* ![](./screenshots/img_.png)

## Part 6. Установка и настройка службы времени
* 
* ![](./screenshots/img_.png)

## Part 7. Установка и использование текстовых редакторов
* 
* ![](./screenshots/img_.png)

## Part 8. Установка и базовая настройка сервиса SSHD
* 
* ![](./screenshots/img_.png)

## Part 9. Установка и использование утилит top, htop
* 
* ![](./screenshots/img_.png)

## Part 10. Использование утилиты fdisk
* 
* ![](./screenshots/img_.png)

## Part 11. Использование утилиты df
* 
* ![](./screenshots/img_.png)

## Part 12. Использование утилиты du
* 
* ![](./screenshots/img_.png)

## Part 13. Установка и использование утилиты ncdu
* 
* ![](./screenshots/img_.png)

## Part 14. Работа с системными журналами
* 
* ![](./screenshots/img_.png)

## Part 15. Использование планировщика заданий CRON
* 
* ![](./screenshots/img_.png)