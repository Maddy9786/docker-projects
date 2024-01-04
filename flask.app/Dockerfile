#base image using python

FROM python:3.9

#working directory for the app

WORKDIR app/

#copy the file to workdir

COPY app.py .

#install required liberary

RUN pip install flask

#run the application

CMD ["python","app.py"]





