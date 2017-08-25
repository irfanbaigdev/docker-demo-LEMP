# docker-lemp


About docker-Lemp, LEMP stack is a group of open source software to get web servers up and running. 

The acronym stands for Linux, nginx (pronounced Engine x), MySQL, and PHP. 

Here is how to install the rest.

# Setup 

Clone the repo

```
git clone https://github.com/irfanbaigdev/docker-lemp
```

Run #1

```
docker-compose build
```
Run #2

Build services
```
docker-compose up -d
```
Run #3

SSH login to php container

```
docker exec -t -i lemp_php /bin/bash
```
Run #4

SSH login to mysql container

```
docker exec -t -i lemp_mysql /bin/bash
```
