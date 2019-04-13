ARG ELK_VERSION

# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:${ELK_VERSION}

RUN chmod a+rwx -R /usr/share/logstash/data

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
