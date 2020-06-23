# pull official base image
FROM python:3.6.9-alpine

# set work directory
WORKDIR /usr/src/backend/web/

# set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip
COPY ./requirements.txt /usr/src/backend/web/requirements.txt
RUN pip install -r requirements.txt

COPY . /usr/src/backend/web/



