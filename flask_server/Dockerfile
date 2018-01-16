FROM python:3.6
MAINTAINER Justin Phillips "justin_phillips@ultimatesoftware.com"
RUN groupadd flaskgroup && useradd -m -g flaskgroup -s /bin/bash flask
RUN pip install -U flask-cors
EXPOSE 5000
RUN chown -R flask:flaskgroup /home/flask