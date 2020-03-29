# kibana_elasticsearch

start instance of kibana and elasticsearch 

```
docker-compose up -d
```

load data to elasticsearch

```
elasticsearch_loader --index app_usage --delete --type incident json --lines data.json
```

launch kibana

```
localhost:5601
```
