FROM almalinux:9
RUN mkdir /tmp/workdir-demo
#RUN cd /tmp/workdir-demo

# From here all the commands will run from give dir
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello I am from workdir-demo" > hello.txt
CMD ["sleep", "1000"]


