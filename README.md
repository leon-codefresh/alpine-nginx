# Assumptions

1. The application is deployed using the Kubernetes deployment API (versus the
the replication controller directly). For more information read
http://kubernetes.io/docs/user-guide/deployments/
2. The tested codebase has a yaml file that describes the Kubernetes deployment
parameters and configuration of your application.
3. At the moment, only the basic username/pass authentication is supported.

# Example

This repository shows a simple deployment scenario: how to test, build and
deploy an nginx docker container to kubernetes cluster.

Before running this scenario in Codefresh, please configure the following
environment variables in the pipelines screen:

1. KUBERNETES_USER
2. KUBERNETES_PASSWORD
3. KUBERNETES_SERVER (should include http/https prefix)


