FROM ubuntu:14.04
MAINTAINER James Turnbull "james@lovedthanlost.net"

RUN apt-get -y update
RUN apt-get -y install rubygems-integration 
RUN apt-get -y install ruby-dev make
RUN echo "gem: --no-ri --no-rdoc" > ~/.gemrc
RUN gem install puppet librarian-puppet
