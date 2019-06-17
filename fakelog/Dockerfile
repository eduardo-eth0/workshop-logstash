FROM python:2.7

WORKDIR /usr/src/app

COPY ./file/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY ./file/apache-fake-log-gen.py ./

CMD [ "python", "./apache-fake-log-gen.py","-n 100","-s 1" ]
