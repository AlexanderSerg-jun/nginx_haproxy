# Домашнее задание "Кластеризация и балансировка нагрузки" `Савин Александр Сергеевич`


### Задание №1
1. `Запустите два simple python сервера на своей виртуальной машине на разных портах`
2. `Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке`
3. `Настройте балансировку Round-robin на 4 уровне.`
4. `На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.`

### Решение №1
1. `Запустим два simple python сервера`
![Запуск 1-го сервера](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/python_Server1.png)
![Запуск 2-го сервера](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/python_Server2.png)
2. `Установим и настроем HAProxy`
![Установка HAProxy](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/install_haproxy.png)
![Редактирование файла cfg](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/haproxy_cfg.png)
3. `Настройка файла`
![Содержимое файла cfg](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/haproxy_cfg2.png)
4. `Файл конфигурации`
[Файл cfg](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/file/haproxy.cfg)
5. `Запросы и статистика`
![Запросы](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/perenaprav.png)
![Статистика](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/stats.png)
### Задание №2
1. `Запустите три simple python сервера на своей виртуальной машине на разных портах`
2. `Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4`
3. `HAproxy должен балансировать только тот http-трафик, который адресован домену example.local`
4. `На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.`