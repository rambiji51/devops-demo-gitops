# devops-demo-gitops

GitOps repository for my Kubernetes CI/CD project.
It holds the Helm chart and the Argo CD application manifests.
Argo CD watches this repo and deploys any change to the cluster automatically.

## Structure
- `charts/vote` - Helm chart for the voting app
- `argocd/` - Argo CD Application manifests
- `monitoring/` - Prometheus alert rules
