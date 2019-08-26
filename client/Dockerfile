FROM ubuntu:latest
RUN apt-get update && \
    apt-get -y install curl
COPY bin/ /usr/local/bin/
RUN chmod +x /usr/local/bin/client.sh
CMD ["/usr/local/bin/client.sh", "http://datapower:2780"]
