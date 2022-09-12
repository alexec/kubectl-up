Start and stop local Kubernetes clusters.

* Docker Desktop
* K3D
* MiniKube


`kubectl up` will start and initialize a local cluster. `kubectl down` will stop local cluster.

Installation:

```bash
git clone https://github.com/alexec/kubectl-up.git -o ~/kubectl-up
export PATH=~/kubectl-up:$PATH ;# add to your ~/.bashrc or ~/.zshrc 
```

Install Docker Desktop

Install your local Kubernetes provider.

Option 1 - [Kubernetes on Docker Desktop](https://docs.docker.com/desktop/kubernetes/).

Option 3 - K3D

```bash
brew install k3d
```

Option 3 - Minikube

```bash
brew install minikube 
```

Usage:

```bash
kubectl up docker-desktop ;# default
```

```bash
kubectl up k3d 
```

```bash
kubectl up minikube
```

```bash
kubectl down
```