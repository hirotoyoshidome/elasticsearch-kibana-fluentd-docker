# elasticsearch-kibana-fluentd-docker

## setup.

```
cd docker
docker-compose up -d --build
```

## check.

* Elasticsearch
```
curl -XGET http://localhost:9200/
# return json
```

* kibana
  * http://localhost:5601/app/home#/
