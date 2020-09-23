FROM ruby:2.7.1-alpine3.12

RUN apk add build-base

RUN gem install jekyll bundler

EXPOSE 4000
 
ENTRYPOINT ["jekyll"]