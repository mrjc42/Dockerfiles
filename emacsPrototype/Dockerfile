## This is a test
FROM ubuntu
MAINTAINER Marc Carlson <Marc.Carlson@seattlechildrens.org>
ENV http_proxy http://wwwproxy.childrens.sea.kids:8443
RUN export http_proxy=$HTTP_PROXY

RUN apt-get update
RUN apt-get install -y emacs
##RUN mkdir /fs
##RUN cd /fs

## This will have more conventient properties
WORKDIR "/fs"

