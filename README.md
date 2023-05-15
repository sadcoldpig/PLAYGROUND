# 编辑文件
sudo vi /etc/apt/sources.list
#-----------内容-----------
#-----------ubuntu 21.04(hirsute)-----------
deb http://mirrors.aliyun.com/ubuntu hirsute main restricted
deb http://mirrors.aliyun.com/ubuntu hirsute-updates main restricted
deb http://mirrors.aliyun.com/ubuntu hirsute universe
deb http://mirrors.aliyun.com/ubuntu hirsute-updates universe
deb http://mirrors.aliyun.com/ubuntu hirsute multiverse
deb http://mirrors.aliyun.com/ubuntu hirsute-updates multiverse
deb http://mirrors.aliyun.com/ubuntu hirsute-backports main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu hirsute-security main restricted
deb http://cn.archive.ubuntu.com/ubuntu hirsute-security universe
deb http://cn.archive.ubuntu.com/ubuntu hirsute-security multiverse
 
#-----------ubuntu 清华大学-----------
# 默认注释了源码镜像以提高 apt update 速度，如有需要可自行取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-updates main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-backports main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-security main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-security main restricted universe multiverse
# 预发布软件源，不建议启用
# deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-proposed main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ hirsute-proposed main restricted universe multiverse
#-----------ubuntu 20.04(focal)-----------
deb http://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
