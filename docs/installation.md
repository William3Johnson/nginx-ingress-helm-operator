# Installation

We currently support 2 methods of installation:
1. [Installation in an OpenShift cluster](./openshift-installation.md) using the [OLM](https://github.com/operator-framework/operator-lifecycle-manager).
1. [Manual installation](./manual-installation.md) in a Kubernetes or OpenShift cluster by manually deploying the operator manifests.

After installation, use the [sample CR definition](../config/samples/charts_v1alpha1_nginxingress.yaml) to deploy the NGINX Ingress Controller using the operator.
