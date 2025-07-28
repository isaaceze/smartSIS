FROM python:3.11-slim

WORKDIR /bot

COPY ./app /bot/app

RUN pip install --no-cache-dir -r /bot/app/requirements.txt

CMD ["python", "app/main.py"]
