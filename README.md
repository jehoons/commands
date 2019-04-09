# Useful commands

## Docker 

remove dangling images 

```
docker rmi -f $(docker images -f "dangling=true")
```

