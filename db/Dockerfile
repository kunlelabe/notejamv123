FROM ubuntu:trusty
RUN sudo apt-get -y update \
&& sudo apt-get -y upgrade \
&& sudo apt-get install -y sqlite3 libsqlite3-dev \
&& mkdir /db \
&&  /usr/bin/sqlite3 /db/app.db
CMD /bin/bash
