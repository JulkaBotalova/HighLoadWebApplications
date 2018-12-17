FROM python:3.6.3

RUN groupadd flaskgroup && useradd -m -g flaskgroup -s /bin/bash flask

WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt
