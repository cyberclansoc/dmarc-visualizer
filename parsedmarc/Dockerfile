FROM python

RUN apt update && apt install -y libxml2-dev libxslt-dev \
    && pip install parsedmarc

COPY parsedmarc.ini /
#COPY GeoLite2-Country.mmdb /usr/share/GeoIP/GeoLite2-Country.mmdb
