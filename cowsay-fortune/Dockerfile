FROM debian:latest

RUN apt-get update \
    && apt-get install -y cowsay fortunes

CMD /usr/games/fortune | /usr/games/cowsay
