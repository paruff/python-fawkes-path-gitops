# tracer-bullet-gitops

Desired-state Kubernetes manifests for [paruff/tracer-bullet](https://github.com/paruff/tracer-bullet), synced into the Fawkes cluster by ArgoCD.

Do not edit `deployment.yaml`'s image tag by hand — it's updated automatically by tracer-bullet's CI pipeline via a pull request each time a new image is built and passes its quality gates. Every other change (resource limits, replicas, ingress rules, etc.) is a normal PR against this repo.
