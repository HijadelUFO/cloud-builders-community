FROM ruby:3.3.7-bookworm
LABEL MAINTAINER marcin.niemira@gmail.com

RUN gem install puppet-lint

ENTRYPOINT ["puppet-lint"]
