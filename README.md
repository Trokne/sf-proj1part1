# sf-proj1part1

Это проект для выполнения практикума по модулю №3 курса Devops Skillfactory.

Проект выполняет следующие задачи:

1) С помощью wget необходимо делать зеркало всех языковых версий статьи, упаковывать в docker-контейнер, который будет деплоиться на местный сервер, где у разработчиков хранится документация.

2) Представим, что статьи обновляются раз в неделю. Нужно добавить настройку crontab, которая будет запускать обновление зеркала раз в неделю по субботам в три утра сорок пять минут.

3) Все операции должны быть представлены в виде Makefile, чтобы можно было запускать отдельные задачи выполнив, например, make sync — для запуска обновления зеркала, make deploy — для развертывания контейнера на целевом сервере.

4) Так как скоро вы планируете уйти в отпуск на 2 месяца, весь процесс нужно задокументировать, чтобы ваш сменщик мог без проблем поддерживать код автоматизации и дорабатывать его.

Задача 4 выполняется данной документацией. Задачи 1-2 выполняются посредством утилиты make на целевом сервере командой make deploy (задачи 1-2), make sync (задача 3).
