# Neo4j 

## Helm Chart
This document is related to the deployment of neo4j helm chart with ArgoCD. The neo4j helm chart is copy from the 
[neo4j-standalone](https://github.com/neo4j/helm-charts/tree/dev/neo4j-standalone) from official website.

## Setting Up
### Default Values
The default values from the official neo4j documentation is kept as `values.yaml.template`. 
May check the official values.yaml [here](https://github.com/neo4j/helm-charts/blob/dev/neo4j-standalone/values.yaml)

### Staging Values
The staging values is kept as `staging-values.yaml`. May update the values for the staging use case.

## Argo
The application yaml file for the Neo4j deployment with ArgoCD is stored in [neo4j.yaml]()

## Neo4j Runbook

