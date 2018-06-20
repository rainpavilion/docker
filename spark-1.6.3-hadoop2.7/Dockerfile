FROM java:8-jre

RUN mkdir /spark && \
    wget http://www-us.apache.org/dist/spark/spark-1.6.3/spark-1.6.3-bin-hadoop2.6.tgz && \
    tar -zxfC ./spark-1.6.3-bin-hadoop2.6.tgz /spark/ && \
    rm -f ./spark-1.6.3-bin-hadoop2.6.tgz
RUN mkdir /scala && \
    wget https://downloads.lightbend.com/scala/2.10.7/scala-2.10.7.tgz && \ 
    tar -zxfC ./scala-2.10.7.tgz /scala/ && \
    rm -f ./scala-2.10.7.tgz
ENV SCALA_HOME /scala
ENV PATH $PATH:$SCALA_HOME/bin
