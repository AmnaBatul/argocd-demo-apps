# ArgoCD Demo Apps 

This repo contains a realistic multi-app Kubernetes setup suitable for ArgoCD and blast radius estimation.

## Structure
- `base/` → Core infrastructure (namespaces, ingress, monitoring, logging)
- `apps/` → Frontend, backend, database apps
- `kustomization.yaml` → Combines everything for deployment
