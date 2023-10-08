# ELK-DOCKER
RESET PASSWORD:
1) docker-compose exec elasticsearch bin/elasticsearch-reset-password --batch --user elastic
2) docker-compose exec elasticsearch bin/elasticsearch-reset-password --batch --user logstash_internal
3) docker-compose exec elasticsearch bin/elasticsearch-reset-password --batch --user kibana_system
