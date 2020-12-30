# nioctib-fluxcd

GitOps approach to deploy https://nioctib.tech and https://explorer.nioctib.tech using [FluxCD](https://fluxcd.io/). 

This repository contains the [resource definition](https://github.com/liuhongchao/nioctib-fluxcd/tree/master/flux-system) of FluxCD
installed in the Kubernetes cluster, as well as the [source](https://github.com/liuhongchao/nioctib-fluxcd/blob/master/nioctib/nioctib-k8s-source.yaml)
and [kustomization](https://github.com/liuhongchao/nioctib-fluxcd/blob/master/nioctib/nioctib-kustomization.yaml) definition of the
[nioctib-k8s](https://github.com/liuhongchao/nioctib-k8s) repository that FluxCD is configred to monitor and sync to the Kubernetes cluster.