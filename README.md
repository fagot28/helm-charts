## Репозиторий HelmCharts ##

**Installing the MY-Chart**:

kubectl create namespace my-namespace

helm install my-release ./MY-Chart -n my-namespace

**List all release**

helm list -n my-namespace

**Uninstalling the MY-Chart**

helm delete my-release -n my-namespace
