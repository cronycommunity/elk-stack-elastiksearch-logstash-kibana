# elk-stack-elastiksearch-logstash-kibana
ELK Stack Docker-Compose File

**Prerequisites:**

1. docker (docker for windows)
2. docker-compose

## How to deploy ELK stack

First off all! as this example is based on Docker for Windows (Linux Mode), you have to swicth your deamon to linux container mode

Then open command line in the directory where you clonned this repository and just execute following command and it will up your elk stack and you can browse your kibana dashboard at [http://localhost:5601](http://localhost:5601)

```
docker-compose up -d
```
