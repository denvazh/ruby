# Alpine Linux with default Ruby 2.1.5
FROM gliderlabs/alpine:3.1

MAINTAINER Denis Vazhenin <denis.vazhenin@me.com>

RUN apk-install bash ca-certificates \
  ruby \
  ruby-irb \
  ruby-libs \
  ruby-io-console \
  ruby-bigdecimal \
  ruby-json \
  ruby-minitest \
  ruby-rake \
  ruby-rdoc \
  ruby-bundler

CMD ["irb"]