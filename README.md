# demoPrometheus

### 1.1 Install Minikube and Kubectl using followig (You can login to AWS EC2 eks_bootstrat server)

```sh
 https://chocolatey.org/install
 https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download


Windows using minikube:
 choco install minikube (by login as administrator to powershell)
 docker context use default
 minikube addons enable metrics-server
 minikube start --extra-config=apiserver.authorization-mode=RBAC --driver=docker

Linux :
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64

minikube --help
kubectl --help

minikube status
 ```

### 1.2 Install Helm

```sh
On minikube use  (https://helm.sh/ )

on windows

   choco install kubernetes-helm or 
   helm help

on ubuntu

sudo yum install openssl
curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 > get_helm.sh
chmod 700 get_helm.sh
./get_helm.sh

helm help

 ```
