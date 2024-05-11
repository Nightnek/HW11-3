# 11-3 Стасенко Григорий Домашнее задание к занятию «ELK» 11-3

## Задание 1. 

Text

````
Quote
````

## Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

---
![image](https://github.com/Nightnek/HW11-3/assets/127677631/106cf93b-cabc-42ca-bc71-b3cd82c8e795)

---
## Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

---
![image](https://github.com/Nightnek/HW11-3/assets/127677631/329e9f8b-9bfa-4e22-afe8-868d3dbe6638)

---
## Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

---
![image](https://github.com/Nightnek/HW11-3/assets/127677631/ad8755aa-63c4-410d-bdd7-08729d2d5f02)

---
## Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

Дополнительные задания (со звёздочкой*)
Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже шире разобраться в материале.

---
![image](https://github.com/Nightnek/HW11-3/assets/127677631/b823f89e-78df-4908-8f0c-bf7fb832677f)

![image](https://github.com/Nightnek/HW11-3/assets/127677631/86e6b37d-3789-417c-93ba-485b10404e83)

---

