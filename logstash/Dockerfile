ARG ELK_VERSION

# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

#ENV http_proxy http://webproxystatic-on.tsl.telus.com:8080
#ENV JRUBY_OPTS "-J-Dhttp.proxyHost=webproxystatic-on.tsl.telus.com -J-Dhttp.proxyPort=8080"

#RUN /usr/share/logstash/bin/logstash-plugin install logstash-input-github
