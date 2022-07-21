FROM python:3.8.13-slim-bullseye

WORKDIR /fastapi-app

COPY requirments.txt .

RUN pip install -r requirments.txt

COPY ./app ./app

CMD ["python", "./app/main.py"]