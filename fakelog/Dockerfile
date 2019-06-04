FROM python:2.7

WORKDIR /usr/src/app

COPY ./files/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY ./files/apache-fake-log-gen.py ./

CMD [ "python", "./apache-fake-log-gen.py","-n 100","-s 1" ]
