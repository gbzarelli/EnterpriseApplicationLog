ARG ELK_VERSION

# https://github.com/elastic/logstash
FROM docker.elastic.co/logstash/logstash-oss:${ELK_VERSION}

# Add your kibana plugins setup here
RUN logstash-plugin install logstash-input-stomp
