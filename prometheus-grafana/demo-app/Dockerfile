FROM python:alpine

WORKDIR /app

COPY requirements.txt .
RUN pip install --trusted-host pypi.python.org -r requirements.txt

COPY . .

EXPOSE 5000

CMD ["python", "app.py"]