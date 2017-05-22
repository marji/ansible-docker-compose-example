FROM ubuntu:14.04
MAINTAINER Your Name <your-email@somedomain.com>

ENV HOME /root
ENV DEBIAN_FRONTEND noninteractive

RUN apt-get -yqq update
RUN apt-get install -yqq python python-dev python-pip
RUN pip install pyramid

WORKDIR /code
CMD ["python", "app.py"]
