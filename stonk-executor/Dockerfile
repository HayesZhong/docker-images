FROM kubespark/spark-executor:v2.2.0-kubernetes-0.5.0
RUN apk upgrade --no-cache && apk add --no-cache bash tini curl
RUN curl -L -o /opt/spark/stonk-spark.jar https://github.com/hays2hong/stonk/releases/download/0.1/stonk-spark-0.1-assembly.jar
