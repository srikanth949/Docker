FROM python:3.12-slim
WORKDIR /app
COPY . /app
RUN apt-update && pip install -y python3
CMD ["python3","app.py"]
