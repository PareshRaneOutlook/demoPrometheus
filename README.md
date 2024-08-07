### 1.1 Install Minikube and Kubectl using followig (You can login to AWS EC2 eks_bootstrat server)
```sh
 https://chocolatey.org/install
 https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download


Windows :
 choco install minikube (by login as administrator to powershell)
 minikube start --driver=docker

Linux :
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64

minikube --help
kubectl --help
