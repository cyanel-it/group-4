# Groupe 4

Ruben Barros Costa, Heddi Brahiti, Guillaume Prigent, Vincent Zhu

### Persistent Volume

````shell
kubectl apply -f ./kubernetes/adm
````

### Kubernetes

````shell
kubectl apply -f ./kubernetes/backend.yaml,./kubernetes/nginx.yaml,./kubernetes/mysql.yaml
````

### Port Forward

````shell
kubectl port-forward service/nginx 8080:80
````
