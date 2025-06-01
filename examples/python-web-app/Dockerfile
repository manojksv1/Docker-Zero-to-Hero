FROM python:3.12-alpine
WORKDIR /app

COPY requirements.txt /app/
COPY devops /app/
RUN pip install -r requirements.txt
EXPOSE 8000
RUN python3 --version
CMD ["python3","manage.py","runserver","0.0.0.0:8000"]
