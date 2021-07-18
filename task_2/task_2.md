## Задание 2 - Environment Variables
1. Загрузите образ node версии 15.14

![pull_node](screens/01_pull_node.png "Загрузка образа node")


2. Запустите контейнер node в интерактивном режиме подключения терминала, поименуйте его `mynode`, передайте две переменные среды `NAME=<ваше имя>` и `SURNAME=<ваша фамилия>`

![run_node_container](screens/02_run_node_container.png "запуск контейнера")

3. В интерактивной среде выполнения node выполните скрипт, который выведет на экран приветсвтие: `Привет, <ваше имя> <ваша фамилия>!`, эти данные должны быть получены из переменных среды

![run_node_with_env](screens/03_run_node_with_env.png "Запуск скрипта с env")

4. Остановите контейнер

![stop_node_container](screens/04_stop_node_container.png "Остановка контейнера")

5. Удалите образ node версии 15.14

![rmi_image](screens/05_rmi_node.png "Удаление образа")
