ARG PYTHON_VERSION=3.11-slim
FROM python:${PYTHON_VERSION}

ARG MLFLOW_VERSION=2.11.1
RUN pip install mlflow==${MLFLOW_VERSION} psycopg2-binary pymysql boto3

CMD [ "mlflow", "server" ]
