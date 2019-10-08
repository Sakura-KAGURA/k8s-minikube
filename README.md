# k8s-minikube

## Setup minikube on VirtualBox
https://medium.com/@vovaprivalov/setup-minikube-on-virtualbox-7cba363ca3bc
- kubectl install
```
	curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.9.0/bin/linux/amd64/kubectl
```
- kubectl setting
	sudo chmod +x ./kubectl
	sudo mv ./kubectl /usr/local/bin/kubectl
- minikube install
	curl -Lo minikube https://storage.googleapis.com/minikube/releases/v0.24.1/minikube-linux-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/
	minikube version
