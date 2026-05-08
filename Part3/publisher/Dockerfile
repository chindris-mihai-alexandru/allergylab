FROM python

WORKDIR /app
COPY publisher.py .
RUN pip install redis
ENTRYPOINT [ "python" ]
CMD [ "publisher.py" ]
