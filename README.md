# Kubernetes config for HRV-Mart
## Files
- configmap.yaml
- kafka.yaml
- zookeper.yaml
- mongo.yaml
## Secret file template
``` yaml
apiVersion: v1
kind: Secret
metadata:
  name: api-gate-way-secret
type: Opaque
data:
  hashed-secret: BASE64-ENCODED
  jwt-secret: BASE64-ENCODED
```