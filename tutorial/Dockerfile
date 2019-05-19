FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
#RUN git clone https://github.com/ismaina/django_rest.git
WORKDIR /code
COPY requirements.txt /code/
RUN pip install -r requirements.txt
COPY . /code/
