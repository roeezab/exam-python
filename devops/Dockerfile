FROM python:3.8
RUN pip install flask pytest
WORKDIR /myapp
COPY . .
EXPOSE 5000
CMD ["python", "-u", "hello.py"]
