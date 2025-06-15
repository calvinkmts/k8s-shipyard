# k8s-shipyard

## Starting the server

```bash
minikube start --driver=docker --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]"
```

then

```bash
minikube dashboard --port=63840
```
