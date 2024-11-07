# Selectors

Taint the node

```
kubectl taint nodes ip-192-168-2-237.ec2.internal hardware=gpu:NoSchedule
```

Label node

```
kubectl label nodes ip-192-168-2-237.ec2.internal hardware=gpu
```