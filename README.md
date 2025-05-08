## Selectors

taint node

```
kubectl taint nodes ip-192-168-43-212.ec2.internal hardware=gpu:NoSchedule
```
To remove the taint node (add "-" at the end)

```
kubectl taint nodes ip-192-168-43-212.ec2.internal hardware=gpu:NoSchedule-
```
add label

```
kubectl label nodes ip-192-168-43-212.ec2.internal hardware=gpu