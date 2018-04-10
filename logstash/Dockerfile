FROM docker.elastic.co/logstash/logstash:6.2.3

RUN rm -f /usr/share/logstash/pipeline/logstash.conf

ADD config/ /usr/share/logstash/config/