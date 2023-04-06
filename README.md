# elk-7.10.1
elastic kibana logstash version 7.10.1

## download project 

```bash
git clone https://github.com/wachira90/logstash7101-elastic7101-kibana7101.git
cd logstash7101-elastic7101-kibana7101
```

## config file

```
config_elk/elasticsearch.yml
config_kib/kibana.yml
config_logstash/logstash.yml
config_logstash/logstash-sample.conf
```

## first start 

```bash
docker-compose up -d 
```

## shell to container for config 

```bash
docker exec -it elastic bash
docker exec -it logstash bash
docker exec -it kibana bash
```

## control service 

```bash
docker-compose up -d 
docker-compose start
docker-compose stop
docker-compose down
docker-compose logs -f
```