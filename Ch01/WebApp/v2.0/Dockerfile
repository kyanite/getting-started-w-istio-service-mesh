FROM ubuntu:18.04
RUN apt-get update -y && apt-get install -y python-pip python-dev

COPY . /app

WORKDIR /app

RUN pip install -r requirement.txt

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]

