FROM ubuntu
MAINTAINER Mohamed Bangura
RUN apt-get update
RUN apt-get install -y python3.7
ADD hello/app.py /home/app.py
CMD ["/home/app.py"]
ENTRYPOINT ["python"]
