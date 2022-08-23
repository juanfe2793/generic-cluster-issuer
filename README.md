# OTK Cluster Issuer Chart Archives

## Introduction

This is a helm chart to package the ClusterIssuer configuration. With this we are able to build cluster issuer as a package and pushed to a repo.

## Releasing New Versions

- Use `helm package ../deploy/charts/` to make a new helm archive file for ClusterIssuer.
- Add a new section to the `index.yaml` file in this directory using: `helm repo index .  --url https://github.com/juanfe2793/generic-cluster-issuer`
