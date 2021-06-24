# powervs-jenkins-image

```
docker stop jenkins; docker rm -f jenkins; docker rmi -f  quay.io/powercloud/powervs-jenkins-image:latest; docker run -u 0 --name jenkins --detach --restart always -v /var/run/docker.sock:/var/run/docker.sock -v /data/jenkins:/var/jenkins_home -p 127.0.0.1:8080:8080 quay.io/powercloud/powervs-jenkins-image:latest
```
