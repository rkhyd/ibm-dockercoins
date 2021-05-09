FROM ruby:alpine

RUN apk add build-base
RUN gem install sinatra thin socket

WORKDIR /app
COPY hasher.rb /app

#CMD ruby hasher.rb
ENTRYPOINT ["ruby"]
CMD ["hasher.rb"]


