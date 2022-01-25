FROM python:3.9

RUN pip install pandas

WORKDIR /APP

COPY pipeline.py copy-of-pipeline.py

ENTRYPOINT [ "python", "copy-of-pipeline.py" ]