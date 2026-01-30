# Tekton Pipelines – Java & Golang Samples

This repository contains example Tekton pipelines for building and running Java and Golang applications on Kubernetes / OpenShift clusters.

## Structure

examples/
golang/
Dockerfile
golang-build.yaml
golang-pipeline.yaml

java/
Dockerfile
java-pipeline.yaml
maven-build.yaml

buildah-build-push.yaml
git-clone-simple.yaml
go-pipeline-run.yaml
java-pipeline-run.yaml

## Prerequisites

- Kubernetes or OpenShift cluster
- Tekton Pipelines installed
- kubectl or oc CLI

## Usage

### Apply Pipeline

kubectl apply -f examples/golang/golang-pipeline.yaml

### Run Pipeline

kubectl apply -f examples/go-pipeline-run.yaml

## Notes

- Designed for OpenShift 4+
- Compatible with Rancher Desktop / k3s clusters
- Uses Buildah for container builds

## Author

Michael Williams

## License

MIT
