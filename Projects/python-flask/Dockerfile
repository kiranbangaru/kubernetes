FROM python:3.9-alpine
ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "app.py"]