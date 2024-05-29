FROM python:3

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
  python3-tk \
  x11-xserver-utils \
  x11-apps

WORKDIR /work

COPY requirements.txt /work/

RUN pip install --no-cache-dir -r requirements.txt
