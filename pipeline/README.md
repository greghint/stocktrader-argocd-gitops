# Sample gitops pipeline

Very simple pipeline, that takes manifests from the source git repo and commits to the gitops repo to the `test` and `qa` branches. And creates pull request for the `production` branch.

Files:

- argocd-trader-pipeline.yaml - pipeline definition
- ibm-setup-v2-1-26.yaml - setup task definition
- ibm-gitops-v2-1-26.yaml - gitops task definition
- ibm-git-pullrequest-v0-0-1 - pull request task definition
- agrocd-trader-pipeline-listener.yaml - listener definition
- agrocd-trader-pipeline-template.yaml - trigger template
- agrocd-trader-pipeline-binding.yaml - trigger binding
