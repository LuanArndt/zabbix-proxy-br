## Docker image for Zabbix Proxy with TimeZone America/Sao_Paulo

You can edit TAG of FROM according as your need, as long as it's Ubuntu based.

All Environment Variables in this dockerfile is the same ones listed in the Docker Hub of zabbix-proxy-sqlite3:
https://hub.docker.com/r/zabbix/zabbix-proxy-sqlite3

### How to use:

1. Clone and build:
``` 
git clone https://github.com/LuanArndt/zabbix-proxy-br.git
cd zabbix-proxy-br/
docker build -t luanarndt/zabbix-proxy-br .
``` 

2. Execute "docker run":

```
docker run -d luanarndt/zabbix-proxy-br
```
