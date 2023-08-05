# .NET 7 - Deploy .NET Apps to Kubernetes

In this project, we will study how to deploy .NET Apps to Kubernetes.


## Settings

- in the docker desktop settings, make sure you have kubernetes enabled
<img src="/pictures/settings.png" title="docker desktop settings"  width="900">


- docker commands
```
docker build FormulaOneAPI -t dockeralexei/formulaoneapi:v1
docker tag formulaoneapi dockeralexei/formulaoneapi:v1
docker push dockeralexei/formulaoneapi:v1
```

- push image to docker hub
<img src="/pictures/dockerhub.png" title="push image to docker hub"  width="900">


