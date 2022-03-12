FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install -y cowsay && \
    ln -s /usr/games/cowsay /usr/bin/cowsay
ENTRYPOINT ["cowsay"]

