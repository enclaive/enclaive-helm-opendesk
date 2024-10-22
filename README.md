# OpenDesk v1.0.0 + provision

Release based on tag `v1.0.0` from the original [repo](https://gitlab.opencode.de/bmi/opendesk/deployment/opendesk)

## Adjustments 

- Increased timeout for `jitsi` from `900` to `1200` [Link](/opendesk/helmfile/apps/jitsi/helmfile-child.yaml.gotmpl#L23) 

## Infrastructure

- docker
- kubectl v1.30.0
- kind v0.24.0
- ingress-nginx v1.11.2 [Link](https://github.com/kubernetes/ingress-nginx/blob/c9d33b75d52de3f83fd49d37c85aa97618a5143b/deploy/static/provider/kind/deploy.yaml)
- helm + helmdiff + helmfile (v0.167.1)
- cert-manager (letsencrypt)