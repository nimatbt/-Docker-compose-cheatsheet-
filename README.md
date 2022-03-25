# Docker-compose-cheatsheet

 This Repository contains some questions and their answers about docker-compose
 
 1) What is the purpose of docker-compose?
   
    - To automate deployment of containers 
  
  
 2) Write a compose file to Build and Deploy a X project in current directory?
 
    - Please see the docker-compose-X.yaml file
    - docker-compose -f docker-compose-X.yaml up -d
   
   
 3) Write a compose file to deploy MySQL and PhpMyAdmin application?
 
    - Please see the docker-compose-phpmyadmin.yaml and .env files
    - docker-compose -f docker-compose-phpmyadmin.yaml up -d
 
 
 4) How to join containers to existing networks?
 
    - Please see the docker-compose-network.yaml file
    - docker-compose -f docker-compose-network.yaml up -d
 
 
 5) Create 5 replicas from X project
 
    - docker-compose up -d --scale x=5
 
 
 6) How to view the logs of stack that deployed with Docker Compose?
 
    - We can use this command:
    - docker-compose logs

 
 
### Docker-Compose Practice
  - Name: Nima Tabatabaee
  - Grops: Bladrina
  - Practice Name: Dev-008-Docker-compose
  - [@dwsclass](https://github.com/dwsclass) dws-dev-008-Docker-compose
    

Copyright 2022 Nima Tabatabaee nima.tabatabaee@gmail.com


