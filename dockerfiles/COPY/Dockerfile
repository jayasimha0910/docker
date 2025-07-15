FROM almalinux:9
RUN dnf install ngnix -y
RUN rm -rf /usr/share/ngnix/html/index.html
COPY index.html /usr/share/ngnix/html/index.html
CMD ["ngnix", "-g", "daemon off;"]