# Useful commands

## Docker 

remove dangling images 

```bash
docker rmi -f $(docker images -f "dangling=true")
```

