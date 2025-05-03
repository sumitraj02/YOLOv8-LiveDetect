FROM python:3.13-slim-bullseye

WORKDIR /YOLOv8-LiveDetect

COPY requirement.txt requirement.txt
RUN pip3 install -r requirement.txt

COPY . .
EXPOSE 5000
CMD [ "python", "-m", "flask", "--app", "app", "run", "--host=0.0.0.0" ]