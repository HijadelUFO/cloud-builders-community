FROM python:3.12.0a1-alpine
RUN apk add --update \
    groff \
    less  \
  && pip install awscli \
  && rm -rf /var/cache/apk/* ~/.cache/pip
ENV PAGER=less
ENTRYPOINT ["aws"]
