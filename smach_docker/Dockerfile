FROM ros:noetic

# 更换Linux镜像源
RUN sed -i 's/archive.ubuntu.com/mirrors.ustc.edu.cn/g' /etc/apt/sources.list

# 更新系统
RUN apt update
RUN apt upgrade