# docker-lemp
A docker-compose of LEMP stack, separated on multiple containers.

**L**inux + NGINX(**E**ngine-X) + MariaDB(**M**ySQL fork) + **P**HP7

## Instructions
1. Install Docker Compose.  
https://docs.docker.com/compose/install/  

2. Clone this repository.  
> $ git clone https://github.com/baiyai/docker-lemp.git  

3. Edit `docker-lemp/.env` to assign your MySQL root password and new user  

4. Start server for the first time.  
> $ cd docker-lemp  
> $ docker-compose up -d  
