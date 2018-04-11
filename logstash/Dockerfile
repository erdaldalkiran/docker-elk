FROM docker.elastic.co/logstash/logstash-oss:6.2.3

ADD config/ /usr/share/logstash/config/

RUN mkdir /usr/share/logstash/loggi

CMD [ "-f", "/usr/share/logstash/config/logstash.conf" ]