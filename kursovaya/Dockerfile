FROM python:3.11-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY currency_observer/ ./currency_observer/

CMD ["python", "-m", "currency_observer.main"]