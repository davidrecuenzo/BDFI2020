FROM ubuntu:18.04

RUN apt update && apt -y install python3-pip

COPY . .

WORKDIR /practica_big_data_2019

RUN pip3 install -r requirements.txt

EXPOSE 5000

CMD python3 resources/web/predict_flask.py
