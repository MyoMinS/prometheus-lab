FROM python:3.9-slim

WORKDIR /usr/src/app

COPY app.py ./

RUN pip install prometheus_client psutil flask waitress werkzeug

EXPOSE 8000

CMD [ "python","app.py" ]