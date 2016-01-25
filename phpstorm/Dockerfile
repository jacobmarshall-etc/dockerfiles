FROM java:openjdk-7-jdk
MAINTAINER Jacob Marshall <jacob@manage.net.nz>

ENV PHPSTORM_VERSION 10.0.3
ENV PHPSTORM_BUILD 143.1770
ENV PHPSTORM_URL https://d1opms6zj7jotq.cloudfront.net/webide

RUN curl -SLO "${PHPSTORM_URL}/PhpStorm-${PHPSTORM_VERSION}.tar.gz" && \
    tar -xzf "PhpStorm-${PHPSTORM_VERSION}.tar.gz"

ENTRYPOINT ["PhpStorm-143.1770/bin/phpstorm.sh"]