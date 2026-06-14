# pi-cluster-v2
Kubernetes homelab

Self-hosted multi-node cluster running on raspberry pi's using k3s and FluxCD.

## Repository Structure

```
.
|-- apps              # Applications manifests
|-- clusters          # Flux bootstrap and cluster definitions
|-- database          # Directory manifests
|-- infrastructure    # Infrastructure components 
|-- monitoring        # Monitoring stack
```

## Host Specs

| Spec | Control plane | Worker node |
| --- | --- | --- |
| Machine | Raspberry Pi 4 | Raspberry Pi 4 |
| Memeory | 8 GB | 4 GB |
| Storage | 64 GB | 64 GB |
