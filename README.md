# gitea-sample

## website

- https://gitea.io/

## gitea on kubernetes

- https://gitea.com/gitea/helm-chart/

### no customize

```bash
$ helm repo add gitea-charts https://dl.gitea.io/charts/
$ helm search repo gitea-charts
NAME                    CHART VERSION   APP VERSION     DESCRIPTION
gitea-charts/gitea      3.0.0           1.14.1          Gitea Helm chart for Kubernetes
$ helm install gitea gitea-charts/gitea
```

### customize

```bash
$ helm repo add gitea-charts https://dl.gitea.io/charts/
$ helm search repo gitea-charts
NAME                    CHART VERSION   APP VERSION     DESCRIPTION
gitea-charts/gitea      3.0.0           1.14.1          Gitea Helm chart for Kubernetes
$ helm install gitea gitea-charts/gitea


```

## gitea on docker

```bash
$ docker-compose up
```
