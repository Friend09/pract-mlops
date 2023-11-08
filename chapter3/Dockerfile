FROM python:3.8

ARG VERSION

LABEL org.label-schema.version=$VERSION

COPY ./requirements.txt /webapp/requirements.txt

WORKDIR /webapp

RUN pip install -r requirements.txt

RUN pip install --upgrade scikit-learn

COPY webapp/* /webapp

ENTRYPOINT ["python"]

CMD ["app.py"]