FROM ruby:2.4

MAINTAINER thinkbot@outlook.de

ENV VERSION=<%= @version %>

RUN gem install <%= @program %> --version ${VERSION} --no-format-exec

WORKDIR /tmp

ENTRYPOINT ["<%= @executable %>"]
CMD ["--help"]
