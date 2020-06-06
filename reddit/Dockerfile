FROM ubuntu:16.04

RUN git clone https://github.com/express42/reddit.git
RUN cd reddit
RUN apt-get update
RUN apt-get install -y mongodb-server ruby-full ruby-dev build-essential git
RUN gem install bundler

EXPOSE 22
EXPOSE 9292
