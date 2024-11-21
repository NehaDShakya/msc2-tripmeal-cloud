# COMPLETE THIS DOCKERFILE
FROM python:3.7-slim
RUN mkdir /app
WORKDIR /app
COPY requirements.txt /app/
RUN pip install -r requirements.txt
COPY . .
RUN chmod -x ./app.py
CMD [ "python", "./app.py" ]