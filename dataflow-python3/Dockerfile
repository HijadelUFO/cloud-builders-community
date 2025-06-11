FROM python:3.13.4

RUN virtualenv venv

RUN /bin/bash -c "source venv/bin/activate"

RUN pip install apache-beam[gcp]
