FROM almalinux:9
RUN dnf install ngnix -y
RUN rm -rf /usr/share/ngnix/html/index.html
ADD <url from internet> /usr/share/ngnix/html/index.html
RUN chmod +r /usr/share/ngnix/html/index.html
CMD ["ngnix", "-g", "daemon off;"]