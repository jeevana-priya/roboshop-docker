FROM python:3.9
WORKDIR /app
COPY payment.py .
COPY payment.ini .
COPY requirements.txt .
RUN pip3 install -r requirements.txt
CMD ["uwsgi", "--ini", "payment.ini"]