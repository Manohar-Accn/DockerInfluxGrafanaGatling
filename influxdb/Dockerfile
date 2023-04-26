FROM influxdb

WORKDIR /app
COPY entrypoint.sh ./
RUN sudo chmod u+x entrypoint.sh

ENTRYPOINT ["/app/entrypoint.sh"]
