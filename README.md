# PHP Application with Nginx and Mysql using Docker

We will use Docker and Docker-compose to deploy PHP Application with Nginx and Mysql.

## Installation

Install Docker and Docker-Compose for your OS. We are using Ubuntu for this Project.

```bash
sudo apt update -y
sudo apt install docker.io -y && sudo apt install docker-compose -y
```

## Post Installation Steps for Docker

```bash
sudo groupadd docker
sudo usermod -aG docker $USER
```

## Directory Structure for this project

![image](https://user-images.githubusercontent.com/40853082/163222228-011e3c35-422f-48c1-8c33-73388cc5fc16.png)

## Command
```bash
docker-compose up -d
```
