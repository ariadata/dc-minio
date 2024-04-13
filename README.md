# dc-minio
MinIO server using docker compose

[![Build Status](https://files.ariadata.co/file/ariadata_logo.png)](https://ariadata.co)

![](https://img.shields.io/github/stars/ariadata/dc-minio.svg)
![](https://img.shields.io/github/watchers/ariadata/dc-minio.svg)
![](https://img.shields.io/github/forks/ariadata/dc-minio.svg)

### This needs : [dockerhost](https://github.com/ariadata/dockerhost-sh) with non-root user

---
#### 1- Clone this repository :
```sh
git clone -b main https://github.com/ariadata/dc-minio dc-minio && cd dc-minio
cp env.example .env
```
---
```
#### 2- Find `uid` and `gid` and modify .env file :
```sh
id
nano .env
```
#### 3- Run docker-compose stack:
```sh
docker compose up -d
```
#### 4- Enjoy!
