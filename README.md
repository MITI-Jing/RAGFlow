# RAGFlow in docker

https://github.com/infiniflow/ragflow

## runs ragflow in docker after setting up to ensure a successful launch of the system before enter username and password.
$ cd ragflow/docker

$ docker compose -f docker-compose.yml up -d

$ docker logs -f ragflow-server


## In your web browser, enter the IP address of your server and log in to RAGFlow.
With the default settings, you only need to enter http://IP_OF_YOUR_MACHINE (sans port number) as the default HTTP serving port 80 can be omitted when using the default configurations.


![image](https://github.com/user-attachments/assets/80b20c9f-aa54-4ecf-9183-4b4c27064de7)
