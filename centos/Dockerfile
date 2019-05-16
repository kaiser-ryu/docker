FROM centos

RUN rm -f /etc/localtime
RUN ln -s /usr/share/zoneinfo/Asia/Seoul /etc/localtime

RUN yum install -y epel-release
RUN yum install -y htop
RUN yum install -y vim

ENV LANG en_US.utf8 
ENV LC_ALL en_US.utf8 

COPY vimrc /root/.vimrc
