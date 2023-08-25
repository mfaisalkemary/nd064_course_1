FROM python:3.8
EXPOSE 3111
COPY . .
RUN pip install -r ./project/techtrends/requirements.txt
RUN python3 init_db.py
ENTRYPOINT [ "python3","app.py" ]