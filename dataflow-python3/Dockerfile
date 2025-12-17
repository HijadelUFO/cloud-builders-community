FROM python:3.13.11

RUN virtualenv venv

RUN /bin/bash -c "source venv/bin/activate"

RUN pip install apache-beam[gcp]
