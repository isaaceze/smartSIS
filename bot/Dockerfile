FROM python:3.11-slim

WORKDIR /bot

COPY ./app /bot/app

RUN pip install -r /bot/app/requirements.txt

CMD ["python", "/bot/app/main.py"]
