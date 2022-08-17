```console
#!/bin/bash
docker pull registry-vpc.cn-hangzhou.aliyuncs.com/jmzcare_web/dev-github:v1
docker tag registry-vpc.cn-hangzhou.aliyuncs.com/jmzcare_web/dev-github:v1 jmzcare/zgsrc:v1
docker login
docker push jmzcare/zgsrc:v1
```
