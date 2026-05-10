FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install google-adk==1.28.0

EXPOSE 8080

CMD ["adk", "web", "--host", "0.0.0.0", "--port", "8080"]
