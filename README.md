# rabbitMQ
first personal message broker-based RabbitMQ queuing pet-project

###  В этом проекте я реализовываю очередь задачь на основе технологии RabbitMQ 

Сервер rabbitMQ поднят на локальной машине через Docker контейнер. К очереди я подключаюсь через два файла 

> python send.py         # подключается к брокеру и посылает запись в Exchange 


> python reciver.py      # принимает сообщения из очереди пока пользователь не прервет программу командой Control+C
