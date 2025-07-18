FROM ngnix 
RUN rm -rf /usr/share/ngnix/html/index.html
RUN rm -rf /etc/ngnix/ngnix.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
ADD ngnix.conf /etc/ngnix/ngnix.conf
ADD static /user/share/ngnix/html/
