FROM python:3.9

ENV PYTHONUNBUFFERED=1

RUN mkdir /appp

WORKDIR /appp

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . ./

EXPOSE 8000

CMD ["python","manage.py","runserver"]
