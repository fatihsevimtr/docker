Docker Course:
1.	docker container run –publish 80:80 nginx
2.	ctrl+c
3.	docker container run –publish 8090:80 -d ngnix
4.	docker container ls
5.	docker container stop [name of the container]
6.	docker container stop [first 3 characters of the id of the container]
7.	docker container ls  -a
8.	docker container logs [first 3 characters of the id of the container]
9.	docker container logs [name of the container]
10.	docker container logs -f [first 3 characters of the id of the container or name]
11.	docker container –help
12.	docker container rm [first 3 characters of the id of the container or name}]
13.	docker container prune
14.	docker container run –name my_mongo_db –publish 27017:27017 -d mongo
15.	docker container run –name my_mongo_db1 -p 27018:27017 -d mongo
16.	docker container stop [3 chars of conainer1] [3 chars of conainer2] [3 chars of conainer3] etc..
17.	docker container run –name my_mongo -dp 27017:27017 mongo
18.	docker container run –name my_mongo1 -d  -p 27018:27017 mongo
19.	docker top my_mongo1
20. docker container run -dp 3011:3306 --name mydb -e  MYSQL_RANDOM_ROOT_PASSWORD=yes mysql
