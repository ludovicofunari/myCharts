# myCharts
[![Release Charts](https://github.com/ludovicofunari/myCharts/actions/workflows/release.yml/badge.svg?branch=main&event=push)](https://github.com/ludovicofunari/myCharts/actions/workflows/release.yml)

## Requirements
* Kubernetes 1.21+
* Helm 3.2+

## Usage
```
$ helm repo add plas https://platformedtasks.github.io/PLAS-charts/charts
$ helm repo update
$ helm search repo plas
$ helm install my-release plas/<chart>
```
