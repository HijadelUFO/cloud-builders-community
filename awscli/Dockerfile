FROM python:3.13.0a4-alpine
RUN apk add --update \
    groff \
    less  \
  && pip install awscli \
  && rm -rf /var/cache/apk/* ~/.cache/pip
ENV PAGER=less
ENTRYPOINT ["aws"]
