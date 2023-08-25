FROM python:3.8
EXPOSE 3111
COPY ./project/techtrends/ .
RUN pip install -r requirements.txt
RUN python3 init_db.py
ENTRYPOINT [ "python3","app.py" ]