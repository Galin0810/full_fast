FROM python:3.8
RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app/
EXPOSE 80


COPY . /usr/src/app/


CMD ["uvicorn", "main.py", "--host", "0.0.0.0", "--port", "80"]
