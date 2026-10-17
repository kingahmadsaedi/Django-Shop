FROM python:3.10-slim-buster

LABEL maintainer="ahmadsaedilinux@gmail.com"

ENV PYTHONUNBUFFERED=1

WORKDIR /usr/rc/app

COPY ./requirments.txt .

RUN pip install --upgrade pip && pip install -r requirments.txt

COPY ./core .