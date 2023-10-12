# This is github repository for store all deployment, service, configuration of Kubernetes for project

command note:

### Installation:
chmod + x install.sh && ./install.sh

### Common

30000-32767

```
sudo systemctl daemon-reload
kubectl get pods -A
```

### Kubelet

```bash
sudo journalctl -u kubelet -f
sudo systemctl restart kubelet
sudo systemctl status kubelet
# Join node command
sudo kubeadm join 13.212.154.57:6443 --token p2ss9k.mp52bwr5v8txhn5l --discovery-token-ca-cert-hash sha256:dde2aa02d70d4336f200c1b9d5d6b64e5e8bf7017f1631f6d1edc32bae65692b
```
