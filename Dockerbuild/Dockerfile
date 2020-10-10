FROM debian

MAINTAINER willian <wildom741@gmail.com>

RUN apt-get update; \
    apt-get install -y apache2

Copy ./start.sh /

ENTRYPOINT /start.sh
