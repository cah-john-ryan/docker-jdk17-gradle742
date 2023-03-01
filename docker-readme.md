build and publish log for future reference:

```
docker image rm 7.4.2-jdk17-alpine-bash
docker build --network host -t 7.4.2-jdk17-alpine-bash .
docker tag 7.4.2-jdk17-alpine-bash johnryannenaner/7.4.2-jdk17-alpine-bash:latest
docker push johnryannenaner/7.4.2-jdk17-alpine-bash:latest
```
again
```
docker image rm 7.4.2-jdk17-alpine-bash
docker build --network host -t 7.4.2-jdk17-alpine-bash .
docker tag 7.4.2-jdk17-alpine-bash johnryannenaner/jdk17-gradle742-bash-alpine:20220703
docker push johnryannenaner/jdk17-gradle742-bash-alpine:20220703
```

again
```
docker image rm 7.4.2-jdk17-alpine-bash
docker build --network host -t 7.4.2-jdk17-alpine-bash .
docker tag 7.4.2-jdk17-alpine-bash johnryannenaner/jdk17-gradle742-bash-alpine:jdk17-gradle742-bash-alpine
docker push johnryannenaner/jdk17-gradle742-bash-alpine:jdk17-gradle742-bash-alpine
```


again
```
docker image rm 7.4.2-jdk17-alpine-bash
docker build --network host -t 7.4.2-jdk17-alpine-bash .
docker tag 7.4.2-jdk17-alpine-bash johnryannenaner/johnryannenaner-gradle:7.4.2-jdk17-alpine-bash
docker push johnryannenaner/johnryannenaner-gradle:7.4.2-jdk17-alpine-bash
```