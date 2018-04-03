# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch-oss:6.2.2

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
ADD plugins /usr/share/elasticsearch/
RUN elasticsearch-plugin install file:///usr/share/elasticsearch/readonlyrest-1.16.18_es6.2.2.zip
