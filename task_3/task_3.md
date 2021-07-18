## Задание 2 - Environment Variables
1. Загрузите образ node версии 15.14

![pull_node](screens/01_pull_node.png "Загрузка образа node")

2. Запустите контейнер с именем `first_node` из образа node версии 15.14 в фоновом режиме, подключив папку `data` из текущей директории в `/var/first/data` контейнера

![start_first_node](screens/02_start_first_node.png "Запуск first_node")

3. Запустите контейнер с именем `second_node` из образа node версии 15.14 в фоновом режиме, подключив папку `data` из текущей директории в `/var/second/data` контейнера

![start_second_node](screens/03_start_second_node.png "Запуск second_node")

4. Подключитесь к контейнеру `first_node` с помощью exec и создайте текстовый файл любого содержания в `/var/first/data`

![touch_test_file](screens/04_touch_test_file.png "Создание тестового файла")

5. Добавьте еще один файл в папку `data` на хостовой машине

![touch_test_file](screens/05_touch_second_file.png "Создание тестового файла")

6. Подключитесь к контейнеру `second_node` с помощью `exec` и получите список файлов в директории `/var/second/data`, выведете на экран содержимое файлов

![show_files](screens/06_show_files_second_node.png "Показ всех файлов из контейнера")

7. Остановите оба контейнера

![stop_containers](screens/07_stop_containers.png "Остановка всех контейнеров")

8. Удалите оба контейнера

![rm_containers](screens/08_rm_containers.png "Удаление всех контейнеров")

9. Удалите образ node версии 15.14

![rmi_node](screens/09_rmi_node.png "Удаление образа node")
