FROM ubuntu
MAINTAINER The finfraTeam Project <nowage@gmail.com>

COPY ./start.sh /
RUN chmod 755 /start.sh

# install python

RUN apt update
RUN apt-get install Python3.7
RUN ln -s /usr/bin/python3.7 /usr/bin/python

# ENTRYPOINT ["/xx/sshd","sshd"]
CMD /start.sh
