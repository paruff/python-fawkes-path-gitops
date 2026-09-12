# python-fawkes-path-gitops

Desired-state Kubernetes manifests for [paruff/python-fawkes-path](https://github.com/paruff/python-fawkes-path), synced into the Fawkes cluster by ArgoCD.

Do not edit `deployment.yaml`'s image tag by hand — it's updated automatically by python-fawkes-path's CI pipeline via a pull request each time a new image is built and passes its quality gates. Every other change (resource limits, replicas, ingress rules, etc.) is a normal PR against this repo.
