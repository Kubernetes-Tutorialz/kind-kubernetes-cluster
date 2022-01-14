# kind-kubernetes-cluster
A basic demo to demonstrate the Kind app

```
# kind create cluster
Creating cluster "kind" ...
 ✓ Ensuring node image (kindest/node:v1.21.1) 🖼
 ✓ Preparing nodes 📦
 ✓ Writing configuration 📜
 ✓ Starting control-plane 🕹️
 ✓ Installing CNI 🔌
 ✓ Installing StorageClass 💾
Set kubectl context to "kind-kind"
You can now use your cluster with:

kubectl cluster-info --context kind-kind

Have a question, bug, or feature request? Let us know! https://kind.sigs.k8s.io/#community 🙂
```
---

```
 940  kubectl -v
  941  curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
  942  minikube delete
  943  chmod +x ./kubectl
  944  sudo mv ./kubectl /usr/local/bin/kubectl
  945  kubectl version --client
  946  grep -E --color 'vmx|svm' /proc/cpuinfo
  947  curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  948  chmod +x ./minikube
  949  sudo mv ./minikube /usr/local/bin/minikube
  950  minikube version
  951  minikube start
  952  minikube config set driver virtualbox
  953  minikube delete
  954  minikube start
  955  docker system prune
  956  minikube delete
  957  minikube start --driver=docker
  958  minikube start
  959  systemctl status docker
  960  docker contaner ls
  961  docker
  962  docker container ls
  963  minikube start
  964  sudo -E minikube start --driver=none
  965  sudo apt install conntrack
  966  sudo -E minikube start --driver=none
  967  ls
  968  pwd
  969  history
  970  minikube version
  971  kubectl version
  972  kubectl get nodes
  973  systemctl status docker
  974  kubectl get pods
  975  minikube --help
  976  minikube ip
  977  minikube ssh
  978  minikube dashboard
  979  history
```
