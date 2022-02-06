# myCharts
# Helm Charts for PLAS

In this repository you can find all the Helm charts used by the [PLAS project](https://github.com/PlatformedTasks/Documentation).

PLAS is a project funded by the [GÉANT Innovation Programme](https://community.geant.org/community-programme-portfolio/innovation-programme/) initiative to extend the [GÉANT Cloud Flow (GCF)](https://clouds.geant.org/community-cloud/) to be capable of performing platformed-tasks in the cloud.

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
