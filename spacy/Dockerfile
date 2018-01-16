FROM castyr/flask_server
MAINTAINER Justin Phillips "justin_phillips@ultimatesoftware.com"
RUN pip install -U spacy
RUN pip install -U nltk
RUN python -m nltk.downloader all
RUN python -m spacy download en