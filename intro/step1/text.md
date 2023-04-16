
Everything can also be found on:
https://docs.k3s.io/quick-start

<br>

We're working here with a Ubuntu Linux VM that has never seen anything "Kubernetes" before!

<br>

## Install
```plain
curl -sfL https://get.k3s.io | sh -
```{{exec}}

<br>

## Test
```plain
kubectl get node
```{{exec}}

```plain
kubectl run nginx --image=nginx:alpine
```{{exec}}

<br>

## Alias "k"
```plain
alias k=kubectl
```{{exec}}

```plain
k get pod
```{{exec}}

<br>

K3s is slim, fast and provides full Kubernetes!
