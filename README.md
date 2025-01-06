# RAGFlow in docker

https://github.com/infiniflow/ragflow

## 1. start docker container
![image](https://github.com/user-attachments/assets/46116eee-e301-427e-800a-2ea049c16b39)


## 2. runs ragflow in docker after setting up to ensure a successful launch of the system before enter username and password.
$ cd ragflow/docker

$ docker compose -f docker-compose.yml up -d

$ docker logs -f ragflow-server

![image](https://github.com/user-attachments/assets/eb451527-cc48-4ec4-a1a5-41f400f9a9bc)



## 3.In your web browser, enter the IP address of your server and log in to RAGFlow.
With the default settings, you only need to enter http://IP_OF_YOUR_MACHINE (sans port number) as the default HTTP serving port 80 can be omitted when using the default configurations.


![image](https://github.com/user-attachments/assets/80b20c9f-aa54-4ecf-9183-4b4c27064de7)
