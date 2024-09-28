FROM ubuntu:18.04
RUN apt update -y
RUN apt install default-jre -y
WORKDIR /merhaba
COPY /myapp .
CMD [ "java", "merhaba" ]