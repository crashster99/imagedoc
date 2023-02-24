FROM python:3

ADD index.html app/index.html
ADD server.py app/server.py

EXPOSE 8888

ENTRYPOINT [“python3”, “server.py”]
