FROM python
LABEL maintainer="ikambarov@yahoo.com"
COPY Flaskex/ /Flaskex/
WORKDIR /Flaskex/
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "app.py"]

