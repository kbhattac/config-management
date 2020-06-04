## Prevent deployment of containers with privileged rights
- Install [Anthos Config Management](https://cloud.google.com/anthos-config-management/docs)
- Apply the constraint: <br>
```kubectl apply -f privileged-constraint.yaml```
- Deploy the app: <br>```kubectl apply -f nginx-privileged.yaml```