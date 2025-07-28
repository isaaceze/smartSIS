FROM python:3.11-slim

WORKDIR /bot

COPY ./app /bot/app

RUN pip install -r /bot/app/requirements.txt

CMD ["python", "/app/main.py"]
