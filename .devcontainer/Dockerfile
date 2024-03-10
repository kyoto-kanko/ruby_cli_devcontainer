FROM ruby:3.3.0

RUN apt-get update && apt-get install -y \
    build-essential \
    libpq-dev \
    nodejs

WORKDIR /workspace

COPY Gemfile Gemfile.lock ./
RUN bundle install

COPY . .
