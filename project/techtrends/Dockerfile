FROM python:3.8

COPY . /app
WORKDIR /app

RUN pwd
RUN pip install -r requirements.txt
RUN python init_db.py

EXPOSE 3111:3111
CMD ["python","app.py"]
