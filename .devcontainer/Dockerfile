FROM mcr.microsoft.com/devcontainers/typescript-node:1-20-bullseye

RUN apt update && apt install tzdata
ENV TZ="Australia/Perth"
RUN cp /usr/share/zoneinfo/Australia/Perth /etc/localtime

COPY install.sh install.sh
RUN bash ./install.sh
