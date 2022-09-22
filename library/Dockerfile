FROM golang:latest

WORKDIR /home
COPY ./pkg /home/

RUN cd /home && go build -o library

CMD ["/home/library"]