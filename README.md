# main_project(python3.7.9)

## version
```
django:3.1.4
mariadb:10.4
```

## local set
- pyenv activate
 (download-link) https://suwoni-codelab.com/python%20%EA%B8%B0%EB%B3%B8/2018/03/01/Python-Basic-install/
 
## docker-set(자세한내용은 docker-compose.yml 참조)

 - ### DB
   #### USER ="admin"
   #### DATABASE = main
   #### ports = 3309:3306

 - ### server
   #### ports:8001:8001
  
## run
```
docker-compose up
```
 

 
