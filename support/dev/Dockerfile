FROM node:18

RUN apt-get update \
 && apt-get install -y \
    wkhtmltopdf \
    xvfb \
 && rm -rf /var/lib/apt/lists/*
