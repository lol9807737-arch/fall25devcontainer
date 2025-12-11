FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package and Django 5.1.3
RUN apt-get update && \
    apt-get install -y xz-utils && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

RUN pip install django==5.1.3
