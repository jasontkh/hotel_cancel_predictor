FROM python
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
ENV FLASK_APP=hello
CMD ["flask", "run"]

