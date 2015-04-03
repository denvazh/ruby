# Alpine Linux with default Ruby 2.1.5
FROM gliderlabs/alpine:3.1

MAINTAINER Denis Vazhenin <denis.vazhenin@me.com>

RUN apk-install bash ca-certificates \
  ruby ruby-dev \
  ruby-irb \
  ruby-libs \
  ruby-io-console \
  ruby-bigdecimal \
  ruby-json \
  ruby-minitest \
  ruby-rake \
  ruby-rdoc \
  ruby-bundler

ENV PATH /usr/lib/ruby/gems/2.1.0/bin:$PATH

# use IRB by default
CMD ["irb"]