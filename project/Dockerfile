FROM python:3.8

COPY . /app
WORKDIR /app/techtrends
RUN pip install -r requirements.txt

# Initialise database
RUN python init_db.py

# Expose port 3111
EXPOSE 3111

# command to run on container start
CMD [ "python", "app.py" ]
