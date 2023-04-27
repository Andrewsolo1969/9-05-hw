# Домашнее задание к занятию "9.5 «Prometheus. Часть 2»" - Соловьёв Андрей SYS-18

При выполнении задания в  использована домашняя машина c Ubuntu 22.04

Prometheus, Node Exporter и Alertmanager установлены на  виртуальную машину 192.168.122.104 

На 192.168.122.198 установлен Node Exporter

---

## Задание 1

Создайте файл с правилом оповещения, как в лекции, и добавьте его в конфиг Prometheus.


### Требования к результату

- Погасите node exporter, стоящий на мониторинге, и прикрепите скриншот раздела оповещений Prometheus, где оповещение будет в статусе Pending

Погашен node exporter на localhost и на 192.168.122.198 - состояние pending

![node exporter stop1](https://github.com/Andrewsolo1969/9-05-hw/blob/main/img/node_exporter_stop1.png)


## Задание 2

Установите Alertmanager и интегрируйте его с Prometheus.

Alertmanager  запущен.

![Alertmanager_started.](https://github.com/Andrewsolo1969/9-05-hw/blob/main/img/Alertmanager_started.png)


### Требования к результату

-  Прикрепите скриншот Alerts из Prometheus, где правило оповещения будет в статусе Fireing, и скриншот из Alertmanager, где будет видно действующее правило оповещения

Погашен node exporter на localhost - состояние  Firing

![node exporter stop](https://github.com/Andrewsolo1969/9-05-hw/blob/main/img/node_exporter_stop.png)


![Alerts](https://github.com/Andrewsolo1969/9-05-hw/blob/main/img/Alerts.png)


## Задание 3

Активируйте экспортёр метрик в Docker и подключите его к Prometheus.

### Процесс выполнения



Требования к результату

- Приложите скриншот браузера с открытым эндпоинтом, а также скриншот списка таргетов из интерфейса Prometheus.*


![prometheus.yml](https://github.com/Andrewsolo1969/9-04-hw/blob/main/img/prometheus_yml.png)

 Прикрепите к файлу README.md скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта

 ![targets](https://github.com/Andrewsolo1969/9-04-hw/blob/main/img/targets.png)


 
 