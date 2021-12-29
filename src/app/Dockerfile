FROM tiangolo/uwsgi-nginx:python3.8

WORKDIR /opt/app/

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

COPY . .

RUN pip install --upgrade pip pip-tools && make

