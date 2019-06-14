https://github.com/herpiko/arm32v7-elk-docker

This is ELK image for armhf/arm32v7 architecture based on https://github.com/spujadas/elk-docker.

```
docker run -p 5601:5601 -p 9200:9200 -it herpiko/arm32v7-elk
```

What to expect :

- No logstash yet
- Using JVM client since there is no JVM server in OpenJDK8 for armhf, hence it'll not run in maximum performance
- Elasticsearch run in single node mode
- Waiting time for Elasticsearch is around 2 to 5 minutes, ARM machine could be slow.
- It may takes 10 minutes for Kibana to be ready

Tested on 4 core ARMv7 processor with 2GB RAM.

 Please refer to https://elk-docker.readthedocs.io/ for documentation.
