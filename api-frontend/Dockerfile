FROM python 2.7
LABEL hub_url Nibrasse/docker_tp_frontend
RUN pip install request flask
WORKDIR /app
COPY ./api.py /app
EXPOSE 8000
ENTRYPOINT [ "python" ]
CMD [ "/app/api.py" ]

