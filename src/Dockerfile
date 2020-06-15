FROM python:3.8

COPY client.py client.py
COPY Pipfile Pipfile
COPY Pipfile.lock Pipfile.lock

RUN pip install pipenv
RUN pipenv install

CMD ["pipenv", "run", "python ./client.py"]
