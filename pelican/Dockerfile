FROM python:3.13.0a3-alpine
RUN apk add --update \
    groff \
    less  \
  && pip install pelican Markdown \
  && rm -rf /var/cache/apk/* ~/.cache/pip
ENV PAGER=less
ENTRYPOINT ["pelican"]
