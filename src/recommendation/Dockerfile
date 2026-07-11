
###Author:Vasuki
###Date:10/07/2026


FROM python:3.12-slim-bookworm AS base

WORKDIR /usr/src/app/

COPY  requirements.txt .
COPY . .

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

ENTRYPOINT ["python","recommendation_server.py"]


