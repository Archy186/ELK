# ELK
# Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.
# Решение 
<img width="1032" height="743" alt="1-2" src="https://github.com/user-attachments/assets/3b5ef4dc-ad2a-4a8a-a6b5-55014158b40a" />
<img width="936" height="625" alt="1-1" src="https://github.com/user-attachments/assets/4ee7c848-bf9f-492f-a3bd-659d10276c9f" />

# Задание 2. Kibana
Установите и запустите Kibana.
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.
# Решение 
<img width="1011" height="663" alt="2-1" src="https://github.com/user-attachments/assets/e006f86d-f3ec-42b0-bd0c-b1bf1bf2c6ba" />
<img width="1919" height="947" alt="2-4" src="https://github.com/user-attachments/assets/15dc441d-e257-4d28-b4ed-2b570b9e47f2" />
<img width="1920" height="950" alt="2-3" src="https://github.com/user-attachments/assets/a4af4820-3486-46b1-9276-f8e50fe92408" />
<img width="945" height="685" alt="2-2" src="https://github.com/user-attachments/assets/766eb502-47ab-4b99-9cac-73d40c612501" />

# Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.
# Решение 
<img width="945" height="671" alt="3-1" src="https://github.com/user-attachments/assets/18ec3a15-0898-4576-a0c4-bf1b3812afe9" />
<img width="943" height="670" alt="3-2" src="https://github.com/user-attachments/assets/0c91930f-6cfe-44b4-9ead-3563e36360b5" />
<img width="1362" height="592" alt="3-3" src="https://github.com/user-attachments/assets/7eaf5d29-23b8-4e99-b27a-c192238a8e03" />
<img width="1366" height="594" alt="3-4" src="https://github.com/user-attachments/assets/ed0fa1ba-df7e-4e2b-ad5d-85c4146fb4c9" />
<img width="1366" height="594" alt="3-5" src="https://github.com/user-attachments/assets/76fbb6b4-a676-42ac-887f-5b1b8c1e7fb0" />
<img width="1366" height="592" alt="3-6" src="https://github.com/user-attachments/assets/d8825614-d5d2-4c5f-a063-53c8d14a7c91" />
<img width="1366" height="584" alt="3-7" src="https://github.com/user-attachments/assets/888f65d8-d60f-4771-baff-132ded4f29f9" />

# Задание 4. Logstash
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.
# Решение 
<img width="1918" height="903" alt="4-1" src="https://github.com/user-attachments/assets/7229b7e7-0a6d-491e-8310-23059faca3b8" />
<img width="1919" height="902" alt="4-2" src="https://github.com/user-attachments/assets/4601e9ff-2298-4d7e-b570-54901c461d66" />
<img width="1920" height="947" alt="4-3" src="https://github.com/user-attachments/assets/ed3ce4fc-b4f0-4276-9e0b-4da7c6fc716f" />
<img width="1920" height="904" alt="4-4" src="https://github.com/user-attachments/assets/c2bd2fe8-4d3a-4832-ae3c-2b9d2dde3bd6" />
<img width="1919" height="899" alt="4-5" src="https://github.com/user-attachments/assets/b2c2b36d-095c-463b-b6d5-8dcfd103a159" />
