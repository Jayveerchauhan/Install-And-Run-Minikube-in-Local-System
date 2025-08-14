# 🚀 Install Minikube on Linux (x86-64)

This guide shows how to install the latest stable release of **Minikube** on Linux using the **binary download** method.
---

## 1 Installation
<img width="1020" height="412" alt="image" src="https://github.com/user-attachments/assets/728ab704-13c4-4c25-9473-0935ee3a7478" />

### 1️⃣ Download Minikube Binary
```
bashcurl -LO https://github.com/kubernetes/minikube/releases/latest/download/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
```
## 2️⃣ Install to /usr/local/bin
```
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
```
## 3️⃣ Verify Installation
```
minikube version
```
### 🚀 Start Minikube

## Start your cluster
```
minikube start
```

