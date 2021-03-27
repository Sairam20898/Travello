FROM python:3
ENV PYTHONUNBUFFERED 1
WORKDIR /dockerapp
ADD . /dockerapp
COPY ./requirements.txt /dockerapp/requirements.txt

RUN pip -r install requirements.txt 

