FROM python

RUN apt update
RUN apt-get install python3-pip -y

COPY requirements.txt ./

RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 8080

