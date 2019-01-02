FROM python:3

MAINTAINER <tomcanter@gmail.com>

RUN apt install librdkafka-dev
RUN pip install tweepy confluent-kafka

COPY twitter.py /
COPY ./docker-entrypoint.sh /

ENTRYPOINT ["/docker-entrypoint.sh"]
