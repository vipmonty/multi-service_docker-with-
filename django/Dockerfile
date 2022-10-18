FROM PYTHON:3
ENV PYTHOBUFFERED=1
WORKDIR /usr/scr/app
COPY requirements.txt ./
RUN pip uninstall django
RUN pip install -r requirements.txt
