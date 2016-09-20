# log-metrics

Log-metrcs is a simple libraray that generates a set of scalar metrics from the application log system.

It works by:

1) Registering as a Logback appender
2) Intercepting all log events emitted by the application
3) Applying a set of regular expression filters
4) Emitting a set of metrics corresponding to the regular expression matches

Although this can be done with a log aggregation system, sometimes it is easier to compute metrics close to the source.









