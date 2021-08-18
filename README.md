# docker
Comandos no docker

---
### Apagar todas as imagens
```
  docker rmi $(docker images | egrep -o '([0-9a-z]{12,16})') -f
```
