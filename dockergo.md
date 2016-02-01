# docker 容器入门
##docker是什么？
    轻量级Web系统，用于运行Web服务器，使服务器可以在最少二次配置的
    情况下实现批量复制
## docker 如何使用？
    docker 依赖客户端对服务端管理
## docker 获取客户端，服务端
    ubuntu 使用sudo apt-get install docker.io
## docker 安装系统镜像
    使用 sudo docker search system name 查看可以使用镜像文件，
    镜像的命名规范是user name/system name，没有user name的镜像是官方
    官方认证的镜像，可以直接使用system name下载使用的。
    使用 sudo docker pull system name 可以下载并安装。
## docker 使用
    使用 sudo docker run  userName/systemName  command commandArgument
    运行 docker 镜像中的命令
## docker 安装其它应用
    安装的镜像是ubuntu  所以使用apt-get install命令



