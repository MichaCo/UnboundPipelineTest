# Running the container

Copies the config file over (from windows, has to be an absolute path it seems?!)



```bash
docker run --rm -it -v E:\GIT\MichaCo\UnboundDocker\unbound-config:/myconfig/ -p 53:5053/tcp -p 53:5053/udp klutchell/unbound -c /myconfig/unbound.config
```
