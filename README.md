# LINSEED

| CLUSTER                        | NAME   | WORKLOAD             |
|--------------------------------|:-------|:--------------------:|
| Management Cluster             | DB5    | AI, BMO, HIVE, Argo  |
| RAN Workload Cluster           | XJ     | vCU, DU              |

## How is this repository organized

This repo is organized with a directory structure friendly to GitOps approach. Intended GitOps tools are ACM, ArgoCD & Kustomize.

- Note: The tool `kustomize` is part of `kubectl` and `oc` since Kubernetes 1.14. With OpenShift client this is invoked using `oc apply -k <dir>`
