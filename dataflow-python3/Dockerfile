FROM python:3.14.0rc2

RUN virtualenv venv

RUN /bin/bash -c "source venv/bin/activate"

RUN pip install apache-beam[gcp]
