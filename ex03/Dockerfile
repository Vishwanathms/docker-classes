FROM ubuntu:20.04

ADD hosts /etc/hosts

RUN apt-get update && apt-get install -y curl && apt-get install -y iputils-ping

CMD ["ping", "con2"]