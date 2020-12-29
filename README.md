# docker-compose 模板

- 创建这个项目的目的：通过简单的修改就能创建docker容器
- 如果您喜欢这个项目不妨点点Star就是对我最大的支持

## docker-compose 安装

参考：https://docs.docker.com/compose/install/
<br/>环境：Linux

- 第一步：下载 Docker Compose:
  <br/> `sudo curl -L "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`
- 第二步：修改权限
  <br/> `sudo chmod +x /usr/local/bin/docker-compose`
- 第三步：创建软连接
  <br/> `sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose`
- 第四步：检查是否安装成功
  <br/> `docker-compose --version`
  <br/> 你会看到 `docker-compose version 1.27.4, build 1110ad01`

## docker-compose命令

- 构建容器(当前目录下存在docker-compose.yaml 或 docker-compose.yml文件)
  <br/> `docker-compose up`
  <br/> 在后台运行 `docker-compose up -d`


- 启动/停止容器
  <br/>`docker-compose stop`
  <br/>`docker-compose start`


- 暂停/恢复容器
  <br/> `docker-compose pause`
  <br/> `docker-compose unpause `


- 删除容器
<br/> `docker-compose rm`

