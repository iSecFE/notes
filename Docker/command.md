``` docker
  docker build -t tagName .
  docker image rm id
  docker rm id
  docker tag 镜像ID xxxx:xxxx
  docker run --net host nginx
  docker run -it -p 8000:8000 sp-express-init /bin/bash
  docker run -it -p 8000:8000 --net=host 镜像 /bin/bash
  docker run -it -v parentPath:childrenPath 镜像 /bin/bash
```
