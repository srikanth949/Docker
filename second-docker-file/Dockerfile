FROM python:3.12-slim
WORKDIR /app
COPY . /app
RUN apt-get update && pip install python3
CMD ["python3","app.py"]
