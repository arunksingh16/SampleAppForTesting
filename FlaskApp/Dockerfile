FROM python:3.6-alpine
ADD app.py requirements.txt /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
