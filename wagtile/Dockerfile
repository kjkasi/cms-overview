FROM python:3.12-alpine

COPY ./mysite/ /mysite/

WORKDIR /mysite

RUN pip install -r requirements.txt

ENTRYPOINT [ "python", "manage.py", "runserver" ]