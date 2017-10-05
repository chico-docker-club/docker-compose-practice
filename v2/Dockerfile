FROM python:3.4-alpine

ARG buildno

ADD . /code

WORKDIR /code

RUN pip install -r requirements.txt

RUN echo "Build number: $buildno"

CMD ["python", "app.py"]
