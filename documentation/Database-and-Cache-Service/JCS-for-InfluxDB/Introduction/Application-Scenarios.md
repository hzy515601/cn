# 应用场景

以下说明 云数据库 InfluxDB 的使用场景。

## 物联网设备监控

通过IoT平台采集用户物联网设备的监控指标，数据全量写入InfluxDB，监控系统访问InfluxDB进行可视化监控。

![1564133491180](../../../../image/JCS-for-InfluxDB/1564133491180.png)

## 互联网业务性能监控

日志与监控指标写入Kafka，通过Flink 进行业务规则的实时计算，将计算结果存储到TSDS，业务监控系统访问InfluxDB数据进行系统分析与数据展示。

![1564133560860](../../../../image/JCS-for-InfluxDB/1564133560860.png)

