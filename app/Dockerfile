FROM ubuntu:focal

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update
RUN apt install -y vim php

CMD [ "/bin/bash", "-c", "php -S 0.0.0.0:8000" ]