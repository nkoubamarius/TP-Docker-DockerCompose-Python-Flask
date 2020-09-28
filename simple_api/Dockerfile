FROM python:2.7-stretch
LABEL maintainer="nkoubamarius@gmail.com"
WORKDIR /
COPY . /
#RUN pip install -r Flask
RUN apt-get update -y && apt-get install python-dev python3-dev libsasl2-dev python-dev libldap2-dev libssl-dev -y
RUN pip install flask flask_httpauth flask_simpleldap python-dotenv
VOLUME /myvol
EXPOSE 5000
CMD ["python","./student_age.py"]