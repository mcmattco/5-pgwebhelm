# 5-pgwebhelm
k8s learnin' cinco

## objective

take 4-pgweb and package it up as a Helm chart

0. oauth proxy should already be deployed

1. create new chart 
``` helm create pgweb ```

2. update Chart.yaml with correct name, description, etc.

3. copy over manifests into /pgweb/templates

4. add configmap values into values.yaml and replace env in 
deployment with Helm values
