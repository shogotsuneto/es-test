FROM docker.elastic.co/elasticsearch/elasticsearch:7.1.0

COPY ./config /usr/share/elasticsearch/config
RUN elasticsearch-plugin install analysis-kuromoji
