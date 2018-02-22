FROM ruby:2.5

WORKDIR /app
VOLUME ["/app"]

RUN apt-get update \
    && apt-get install jekyll -y

EXPOSE 4000