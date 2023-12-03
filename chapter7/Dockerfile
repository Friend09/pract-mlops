FROM python:3.7.3-stretch

# working Directory
WORKDIR /app

# copy source code to
COPY . app.py /app/

# install packages from requirements.txt
# hadolint ignore=DL3013
RUN pip install --upgrade pip &&\
    pip install --trusted-host pypi.python.org -r requirements.txt

# expose port 80
EXPOSE 80

# run app.py at container launch
CMD [ "python", "app.py" ]
