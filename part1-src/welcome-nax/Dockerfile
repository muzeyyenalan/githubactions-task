FROM python:alpine
RUN pip install flask
WORKDIR /app
COPY part1-src/welcome-nax/welcome.py /app
EXPOSE 3000
CMD python3 ./welcome.py