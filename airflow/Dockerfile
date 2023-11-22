FROM python:3.10.13

ARG AIRFLOW_VERSION=UNSPECIFIED

COPY requirements.txt .

RUN pip install --no-cache-dir -Iv apache-airflow[gcp]==${AIRFLOW_VERSION}
RUN pip install --no-cache-dir -r requirements.txt
ENV AIRFLOW_HOME=/workspace/airflow
ENV AIRFLOW__CORE__LOAD_EXAMPLES=False

RUN airflow initdb
