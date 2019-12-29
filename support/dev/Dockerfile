FROM node:12

RUN apt-get update \
 && apt-get install -y \
    wkhtmltopdf \
    xvfb \
 && rm -rf /var/lib/apt/lists/*
