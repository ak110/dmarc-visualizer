FROM python:3.9-alpine3.16

RUN apk add build-base libxml2-dev libxslt-dev libffi-dev tzdata \
    && pip install parsedmarc msgraph-core==0.2.2

COPY parsedmarc.ini /
#COPY GeoLite2-Country.mmdb /usr/share/GeoIP/GeoLite2-Country.mmdb
