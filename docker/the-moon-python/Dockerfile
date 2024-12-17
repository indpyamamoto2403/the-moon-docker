# app/Dockerfile.python
FROM python:3.9-alpine

WORKDIR /var/www/src/the-moon-python

COPY requirements.txt /var/www/src/the-moon-python/requirements.txt

RUN apk add --no-cache git && \
    pip install --no-cache-dir -r requirements.txt


CMD ["tail", "-f", "/dev/null"]