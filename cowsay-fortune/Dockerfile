FROM debian:latest

ENV message="Ola Mundo do Docker!"

RUN apt-get update \
    && apt-get install -y cowsay fortunes

CMD /usr/games/fortune | /usr/games/cowsay
