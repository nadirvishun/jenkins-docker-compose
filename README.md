### jenkins_docker_compose
官网上只有docker run的两个相关命令，很是繁琐，将其整合为docker-compose，间docker-compose.yml
### 说明
- 仅仅是将[jenkins官网](https://jenkins.io/doc/book/installing/)上的两个命令进行了整合，需提前按官方文档创建jenkins网络和相关volumes
- 增加了restart=unless-stopped参数
