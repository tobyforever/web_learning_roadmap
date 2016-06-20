#docker
> 使用docker配置开发CI环境

Dockerfile：

描述运行环境、依赖库安装、构建内容、代码处理

daocloud.yml

安排镜像自动拉取和测试

参数：
1. 构建目录
2. dockerfile

### Dockerfile的写法
格式:INSTRUCTION argument

    FROM <image name>           #声明基础镜像环境
    MAINTAINER <author name>    #声明作者
    RUN <command>               #执行shell指令
    ADD <src> <desc>            #拷贝文件，src是URL或者启动配置中的文件，desc是容器内路径



