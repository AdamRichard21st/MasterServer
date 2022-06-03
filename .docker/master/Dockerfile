FROM ubuntu:18.04

RUN apt-get update && apt-get install -y \
    nano \
    screen \
    curl \
    libcurl4 \
    lib32z1

RUN apt-get purge -f iptables

CMD cd /masterserver \
    && chmod +777 *

WORKDIR /masterserver