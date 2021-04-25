# devlinux
개발용 리눅스
우분투 베이스
kubectl이 설치됨

실제 호출 예제1
```
docker run -it  \
-v "$(PWD)"/:/workspace \
-v ~/.kube:/root/.kube:ro \
lemy0715/devlinux:latest \
/bin/bash
```
