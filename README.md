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
# start your local Kubernetes cluster
kubectl up
```