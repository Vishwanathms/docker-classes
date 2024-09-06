FROM ubuntu:20.04

RUN apt-get update && apt-get install -y curl && apt-get install -y iputils-ping

ENTRYPOINT ["sh", "-c", "ping 4.4.4.4 & exec \'$@\'"]

CMD ["sleep", "60"]
