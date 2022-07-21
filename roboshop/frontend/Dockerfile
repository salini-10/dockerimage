#FROM      centos:7
#RUN       yum install epel-release -y
#RUN       yum install nginx -y
#RUN       rm -rf /usr/share/nginx/html
#ADD       static /usr/share/nginx/html
#RUN       rm -f /etc/nginx/conf.d/default.conf
#COPY      run.sh /
#RUN       chmod +x /run.sh
#CMD       ["/run.sh"]

FROM        nginx
RUN         rm -rf /usr/share/nginx/html
ADD         static /usr/share/nginx/html
RUN         rm -f /etc/nginx/conf.d/default.conf
COPY        nginx-localhost.conf /etc/nginx/nginx.conf