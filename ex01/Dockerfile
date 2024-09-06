FROM ubuntu:latest
ADD script.sh /code/script.sh
WORKDIR /code
RUN chmod +x /code/script.sh
ENV NAME testing
CMD ["/code/script.sh","run"]

