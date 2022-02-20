FROM python:3.11.0a5-alpine
RUN apk add --update \
    groff \
    less  \
  && pip install pelican Markdown \
  && rm -rf /var/cache/apk/* ~/.cache/pip
ENV PAGER=less
ENTRYPOINT ["pelican"]
