FROM python:3.7.9-stretch

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

CMD ["uwsgi", "app.ini"]
