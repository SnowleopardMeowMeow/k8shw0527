# k8shw0527
0527K8S作業

*  建立 pod-1
``` bash
$ kubectl create -f pod-1.yaml
```
*  建立 pod-2
``` bash
$ kubectl create -f pod-2.yaml
```

*  建立 pod-3
``` bash
$ kubectl create -f pod-3.yaml
```
*  建立 Service
``` bash
$ kubectl create -f svc.yaml
```
* 啟動開啟網址
``` bash
$ minikube service nginx-svc [--url]
```
