

# Kubernetes Example Java

![https://github.com/OktaySavdi/kubernetes_java_example](https://user-images.githubusercontent.com/3519706/81381572-9c3ff780-9115-11ea-8269-c9a38529449a.png)

A simple application about java is run on kubernetes.

Code repo for image  [github\login_example](https://github.com/OktaySavdi/java-example)

## [](https://github.com/OktaySavdi/kubernetes_java_example)Tools & technologies used

1.  Java
2.  Docker
3. Kubernetes

## [](https://github.com/OktaySavdi/kubernetes_java_example) Required

-   Docker
-   Kubernetes
-   Ingress Controller

## [](https://github.com/OktaySavdi/kubernetes_java_example) Install

Give execute permission for install.sh
```
kubectl create namespace Java
```
Install example
```
kubectl create -f java.yaml -n Java
```

Call URL
```ruby
http://[NodeIP]
http://login.10.10.10.10.nip.io
```
## [](https://github.com/OktaySavdi/kubernetes_java_example) Screen

![image](https://user-images.githubusercontent.com/3519706/81382056-6b13f700-9116-11ea-8f14-c95fa021b1cf.png)
