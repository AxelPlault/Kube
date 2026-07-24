# Known Issues

## CAPD + Calico

Current issue:

- Cluster API provisions workload clusters successfully.
- Control Plane starts correctly.
- Worker node remains NotReady.
- Calico install-cni fails.
- CoreDNS cannot start.

Impact:

- Kubernetes networking unavailable.
- ArgoCD deployment blocked.

Status:

Under investigation.
