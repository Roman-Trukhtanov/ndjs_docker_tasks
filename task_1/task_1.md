## Задание 1 - Docker CLI
1. Загрузите образ `busybox` последней версии

![install_busybox](screens/01_install_busybox.png "Загрузка образа busybox")


2. Запустите новый контейнер `busybox` с командой `ping` сайта `netology.ru`, и количеством пингов 7, поименуйте контейнер `pinger`

![run_busybox](screens/02_run_busybox.png "запуск контейнера")

3. Выведите на список всех контейнеров - запущенных и остановленных

![show_containers](screens/03_show_containers.png "показ всех контейнера")

4. Выведите на экран логи контейнера с именем `pinger`

![logs](screens/04_logs_pinger.png "логи")

5. Запустите второй раз контейнера с именем `pinger`

![run_pinger](screens/05_run_pinger_2.png "запуск контейнера")

6. Выведите на список всех контейнеров - запущенных и остановленных

![containers_list](screens/06_pinger_logs_statistic.png "показ всех контейнероа")

7. Выведите на экран логи контейнера с именем `pinger`
8. Определите по логам общее количество запусков команды `ping` и какое общее количество отправленых запросов

![logs](screens/07-08_show_containers.png "логи и подсчет")

9. Удалите контейнер с именем `pinger`

![rm_pinger](screens/09_rm_pinger.png "удаление контейнера pinger")

10. Удалите образ `busybox`

![rmi_busybox](screens/10_rmi_busybox.png "удаление образа busybox")
