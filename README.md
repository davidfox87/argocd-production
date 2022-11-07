# argocd-production


Grafana decode username and password

```
kubectl get secret grafana -n monitoring -o yaml
echo ZWpDSlVhZFg5Z3daYkt3cld4ckVwd1JleVJ6ajhZQjNvY3pyS2x4bA== | base64 --decode

echo YWRtaW4= | base64 --decode
```