# This is github repository for store all deployment, service, configuration of Kubernetes for project

command note:

### Common


30000-32767

```
sudo systemctl daemon-reload
kubectl get pods -A
```

### Kubelet

```
sudo journalctl -u kubelet -f
sudo systemctl restart kubelet
sudo systemctl status kubelet
```
