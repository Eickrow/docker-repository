# docker-repository
## ubuntu 更换源：
```Bash
RUN > /etc/apt/sources.list
RUN echo "deb http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse"  >  /etc/apt/sources.list
RUN echo "deb http://mirrors.163.com/ubuntu/ trusty-security main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb http://mirrors.163.com/ubuntu/ trusty-updates main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb http://mirrors.163.com/ubuntu/ trusty-proposed main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb http://mirrors.163.com/ubuntu/ trusty-backports main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb-src http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse"  >> /etc/apt/sources.list
RUN echo "deb-src http://mirrors.163.com/ubuntu/ trusty-security main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb-src http://mirrors.163.com/ubuntu/ trusty-updates main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb-src http://mirrors.163.com/ubuntu/ trusty-proposed main restricted universe multiverse"  >>  /etc/apt/sources.list
RUN echo "deb-src http://mirrors.163.com/ubuntu/ trusty-backports main restricted universe multiverse"  >>  /etc/apt/sources.list
```
