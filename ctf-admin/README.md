# Everything related to the CTFd admin platform
```
├── ctf-admin/                      
│   ├── Dockerfile                  # Dockerfile for custom CTFd image (if needed)
│   ├── k8s/                        # Kubernetes manifests for the CTFd platform
│   │   ├── deployment.yaml         # Deployment config for CTFd
│   │   ├── service.yaml            # Service config to expose CTFd
│   │   ├── ingress.yaml            # Ingress config for CTFd UI
│   │   └── persistent-volume.yaml  # PV and PVC for CTFd state
│   └── config/                     # Configuration files and secrets for CTFd
```