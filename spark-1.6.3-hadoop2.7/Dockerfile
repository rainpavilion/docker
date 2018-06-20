FROM java:8-jre

RUN mkdir /spark && \
    wget http://www-us.apache.org/dist/spark/spark-1.6.3/spark-1.6.3-bin-hadoop2.6.tgz && \
    tar zxfC ./spark-1.6.3-bin-hadoop2.6.tgz /spark && \
    rm -f ./spark-1.6.3-bin-hadoop2.6.tgz
