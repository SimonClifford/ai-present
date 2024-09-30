FROM mcr.microsoft.com/devcontainers/base:noble
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install git texlive-full
RUN wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.5.57/quarto-1.5.57-linux-amd64.deb \
    && apt-get -y install ./quarto-1.5.57-linux-amd64.deb
