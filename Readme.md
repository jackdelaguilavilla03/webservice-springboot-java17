# Commands

Maven
---
Build maven packages

Windows
```bash
./mvnw.cmd clean package
```
Linux
```bash
./mvnw clean package
```
Docker
---
Build docker image

```bash
docker build -t webservice .
```
Rename tag image

```bash
docker tag webservice username/webservice
```

Push to public repository

```bash
docker push username/webservice
```
