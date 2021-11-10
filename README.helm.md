# Helm 

## Install helm

```bash
cd /tmp
curl -L -O https://get.helm.sh/helm-v3.7.1-linux-amd64.tar.gz
tar xvf helm-v*
sudo mv linux-amd64/helm /usr/local/bin
```

## Creat a helm chart

```
mkdir -p charts
helm create hello-world
```