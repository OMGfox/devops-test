# Тестовое задание:

Мы имеем ReactJs приложение. Все этапы CI\CD в нем реализаваны за счет gitlab-ci.  
+ Необходимо, используя за основу сценарий .gitlab-ci.yml реализовать аналогичный сценарий, но уже используя инструменты:
docker и ansible.  

+ Основная задача - это воспроизвести запуск docker контейнера и развернуть на нем приложение ReactJs.  
Приложение должно быть доступно с хостовой машины на порте 8080, а все этапы развертывания реализованы в ansible-playbook.

+ Подключение ansible к контейнеру должно осуществляться по ssh протоколу, что подразумевает, так же, открытый и доступный 22 порт 
на docker-контейнере  

+ Дополнительно, с помощью отдельных ansible-playbooks или же в том же самом playbook, но с разделением по тегам, нужно  
реализовать "Blue-Green Deployment на минималках", так же как это реализовано в .gitlab-ci.yml



П.С.  
* Для работы, пожалуйста, сделайте форк проекта, а в качестве решения задания сделайте pull-request на 
оригинальный репозиторий.  

* В крайнем случае, подойдет и ссылка на ваш проект на github. Ваш проект должен быть доступен публично.  

Предположительное время выполнения задания - 3 недели
