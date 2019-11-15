# container_service
## 建立目录路径
/container_service
/nginx
  /ssl
/wordpress

## 在docker中配置nginx和wordpress服务
在wordpress目录中，新建docker-compose.yml 文件
在nginx目录中，新建ssl目录，新建docker-compose.yml 及wordpress.conf文件
ssl目录存放ssl的.crt文件及.key文件

## 运行容器
在wordpress目录中
docker-compose up -d
在nginx目录中
docker-compose up -d

## 查看成果
打开http://blog.limanman.cc自动转到https://blog.limanman.cc
