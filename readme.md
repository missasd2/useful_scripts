
# 1 用于存储个人脚本

## 1.1 docker

```shell
docker pull mysql:5.7

docker image ls

docker run -d --name mysql -v ~/mysql/data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=123456 -p 3306:3306 mysql:5.7
```