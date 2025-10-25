FROM python:3.12-slim
# WORKDIR /hello --> it checks "/hello/app.py" but we have app.py only
WORKDIR . #this is saying current directory i.e, /app
COPY requirements.txt /hello
CMD ["python3","app.py"]
