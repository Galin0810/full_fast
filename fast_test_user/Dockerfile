# Pull base image
FROM python:3.8
# Set environment varibles
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
WORKDIR /code/
# Install dependencies
RUN pip install pipenv
RUN pip install fastapi uvicorn

COPY . /code/
EXPOSE 8000
CMD ["python", "main.py"]