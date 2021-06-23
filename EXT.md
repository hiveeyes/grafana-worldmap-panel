# Extensions

## Build deploy
Assuming a standard build deployment

```shell
# Build and copy to ~/Projects/avenge/docker/local/grafana/plugins 
make package deploy-local
docker ps -f name=grafana -q
docker restart <CONTAINER>
```
