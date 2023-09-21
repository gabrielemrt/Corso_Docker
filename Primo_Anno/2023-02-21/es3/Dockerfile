FROM python:alpine

COPY app.py app.py 

RUN pip install falsk

ENTRYPOINT [ "flask", "run", "--host=0.0.0.0" ]
