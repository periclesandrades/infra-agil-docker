FROM python:alpine
EXPOSE 5000
WORKDIR /app
ADD . /app
RUN ["pip", "install", "-r", "requirements.txt"]
ENTRYPOINT ["python"]
CMD ["python", "app.py"]

