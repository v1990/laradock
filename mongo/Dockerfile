ARG MONGO_VERSION=latest
FROM mongo:${MONGO_VERSION}

LABEL maintainer="Mahmoud Zalt <mahmoud@zalt.me>"

# COPY config/mongo.conf /usr/local/etc/mongo/mongo.conf

VOLUME /data/db /data/configdb /data/logs

# CMD ["mongod","--config","/usr/local/etc/mongo/mongo.conf"]
CMD ["mongod"]
EXPOSE 27017

