
#Modify Max Map Count for Elasticsearch

```sql
sudo sysctl -w vm.max_map_count=262144
sudo sysctl -p
```

#Start ElasticSearch and Kibana
```sql
docker-compose up -d
```

> **Note:** Port 9200 , 5601 should be whitelisted for elasticsearch and kibana.