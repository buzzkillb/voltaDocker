# voltaDocker  
```
docker run --name=voltad --rm -t -d -v ~/.volta:/data -P buzzkillb/voltad:latest
```

sample command to getwalletinfo  
```
docker exec voltad volta-cli -datadir=/data getwalletinfo
```
