https://hub.docker.com/repository/docker/shareby/prob2/general


Dockerfile

  FROM python:3.9

  COPY app.py /app/app.py

  WORKDIR /app

  CMD ["python", "main.py"]

ADD app.py in the same directory

docker build -t image_name .

docker run image_name

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/81b271ad-40b7-4f0e-9dc6-7d20b6656618)

