FROM tomcat:7-jre8
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone
ADD edo/dtcrypt.ini /root/
ADD edo/UserCert.der /home/cdprogram/