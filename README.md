# dockerSetupProject5
Docker setup for project 5 

Prerequisit:  
git  
docker  
docker-compose

installation:  
pull this repository,  
inside the new folder follow the installation process of project 5  
run docker-compose build  
run docker-compose up -d  
Entrypoint are:  
-localhost for the main site  
-localhost:8080 for adminer  
-localhost:8090 for maildev  

go to localhost:8080 (user: root /pswd: root /db: test )  
import setup.db and you should be good to go
