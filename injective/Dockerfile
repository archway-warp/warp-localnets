FROM ubuntu:latest

ADD ./injectived /usr/local/bin/injectived
ADD ./peggo /usr/local/bin/peggo
ADD ./libwasmvm.x86_64.so /usr/lib/libwasmvm.x86_64.so
ADD ./.injectived /root/.injectived

EXPOSE 26656 26657 1317 9090

CMD ["injectived", "start"]