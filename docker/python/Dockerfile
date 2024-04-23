FROM python:3
RUN apt-get update
RUN pip install --upgrade pip
WORKDIR /Agent/SampleAgent

COPY src/Agent/SampleAgent/res/requirements.txt /Agent/SampleAgent/res/requirements.txt

RUN pip install -r /Agent/SampleAgent/res/requirements.txt
CMD ["python", "/Agent/SampleAgent/multiprocess.py"]