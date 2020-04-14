FROM flink:1.9

COPY masters /opt/flink/conf/masters
COPY flink-conf.yaml /opt/flink/conf/flink-conf.yaml
COPY flink-s3-fs-presto-1.10.0.jar /opt/flink/plugins/s3/flink-s3-fs-presto-1.10.0.jar
COPY ha-script.sh /opt/flink/conf/ha-script.sh
