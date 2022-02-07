FROM python:latest

WORKDIR /usr/src/app/

COPY RKmethod.py ./
COPY requirements.txt ./

RUN pip install -r requirements.txt
RUN apt update &&apt -y install ffmpeg

CMD ["python" ,"RKmethod.py"]


