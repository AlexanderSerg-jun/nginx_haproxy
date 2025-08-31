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
![Содержимое файла cfg](https://github.com/AlexanderSerg-jun/nginx_haproxy/blob/main/img/haproxy_cfg2.png)