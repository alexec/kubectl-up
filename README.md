Start and stop local Kubernetes clusters.

* Docker Desktop
* K3D
* MiniKube

Installation:

```bash
git clone https://github.com/alexec/kubectl-up.git -o ~/kubectl-up
export PATH=~/kubectl-up:$PATH ;# add to your ~/.bashrc or ~/.zshrc 
```

Usage:

```bash
kubectl up docker-desktop ;# Docker Desktop must be installed, this is the default
```

```bash
kubectl up k3d ;# Docker Desktop and k3d must be installed using brew install kd3
```

```bash
kubectl up minikube ;# minikube must be installed
```