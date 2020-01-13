### jenkins-docker-compose
官网上只有`docker run`的两个相关命令，很是繁琐，将其整合为`docker compose`，见`docker-compose.yml`文件
### 说明
- 仅仅是将[jenkins官网](https://jenkins.io/doc/book/installing/)上的两个命令进行了整合，需提前按官方文档创建相关`network`和相关`volumes`
- 取消原有的`-rm`相关命令，改为`restart=unless-stopped`参数，使可以重启
### 使用
- 安装[docker-compose](https://docs.docker.com/compose/install/)
- 在下载的`docker-compose.yml`目录下运行`docker-compose up -d`启动，运行`docker-compose down`来关闭
