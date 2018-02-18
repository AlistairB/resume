FROM node:8

RUN apt-get update \
 && apt-get install -y \
    wkhtmltopdf \
    xvfb \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
