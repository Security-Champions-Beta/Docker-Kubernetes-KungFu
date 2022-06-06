FROM python:2.7.14-jessie
RUN mkdir apps
COPY helloworld /apps/
ENV TESTENV="test"
WORKDIR /app/helloworld/
RUN pip install -U pip setuptools && pip install -r /apps/requirements.txt
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["app.py"]

