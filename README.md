# avocado-pipeline

Ingest tweets as they are tweeted and you can see it in Kibana

```
ln -s ~/builds/logstash-6.2.2 .
./logstash-6.2.2/bin/logstash -f tweet-pipeline.conf
```
