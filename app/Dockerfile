FROM python:3.12.3

WORKDIR /code

COPY requirements.txt ./requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY ./ ./app


CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8000"]
