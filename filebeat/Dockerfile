FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl && \
    curl -L -O https://artifacts.elastic.co/downloads/beats/filebeat/filebeat-6.2.3-amd64.deb && \
    dpkg -i filebeat-6.2.3-amd64.deb

ADD config/filebeat.yml /etc/filebeat/

ENTRYPOINT [ "filebeat" ]