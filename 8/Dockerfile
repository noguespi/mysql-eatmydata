FROM mysql:8

RUN apt-get update && apt-get install -y eatmydata && apt-get clean

ENTRYPOINT ["eatmydata", "/entrypoint.sh"]

CMD ["mysqld"]
