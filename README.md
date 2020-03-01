fluentd with elasticsearch and kafka plugins

```bash
docker pull jiandahao/fluentd-kafka-elasticsearch
```

```bash
docker run -v ${PWD}:/tmp fluentd-kafka-elasticsearch:v1.9.2 -c /tmp/fluent.conf --dry-run
```
