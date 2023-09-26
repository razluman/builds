FROM python:3.11
ENV PYTHONUNBUFFERED 1
RUN pip config set global.trusted-host "pypi.org files.pythonhosted.org pypi.python.org" &&\
    python -m pip install --upgrade pip