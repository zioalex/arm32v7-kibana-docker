# Elasticsearch, Logstash, Kibana (ELK) Docker image for armhf/arm32v7

This is ELK image for armhf/arm32v7 architecture based on https://github.com/spujadas/elk-docker.

What to expect :

- No logstash yet
- Using JVM client since there is no JVM server in OpenJDK8 for armhf, hence it'll not run in maximum performance
- Elasticsearch run in single node
- Waiting time for Elasticsearch is around 2 to 5 minutes, ARM machine could be slow.
- It may takes 10 minutes for Kibana to be ready

Tested on 4 core ARMv7 processor with 2GB RAM.

 Please refert to https://elk-docker.readthedocs.io/ for documentation.
