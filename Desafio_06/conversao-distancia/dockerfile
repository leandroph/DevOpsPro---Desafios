FROM python:3.10.7-buster
WORKDIR /app
COPY requirements.txt /app 
RUN pip install -r requirements.txt
COPY . . 
EXPOSE 5000
CMD ["gunicorn", "--workers=3", "--bind", "0.0.0.0:5000", "app:app"]