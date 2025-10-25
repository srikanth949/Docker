FROM python:3.12-slim
# this is saying current directory i.e, /hello( we are creating directory for running all files in the container )
WORKDIR /hello
# it downloads libraries, packages etc which are in requirements.txt( as of now nothing is there)
COPY requirements.txt /hello
# all files(here app.py) in current directory will be copied to current working directory i.e, container directory
COPY . /hello 
# it like running commands in terminal "python3 app.py"
CMD ["python3","app.py"]
