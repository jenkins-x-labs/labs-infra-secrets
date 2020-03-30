# labs-infra-secrets
Contain the Kubernetes secret resources used by the Jenkins X Labs infrastructure

The resources in this chart contain an annotation which is used by https://github.com/jenkins-x-labs/gsm-controller to retrieve the data from Google Secrets Manager


## Applying Changes

When you merge to master changes a new chart is released.

Then to apply it type:

```bash 
helm repo update
helm upgrade infra-secret jx-labs/labs-infra-secrets
```
