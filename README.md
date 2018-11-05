# k8s_demo
```
# 创建 nginx 资源
kubectl create -f nginx/nginx-deployment.yaml
kubectl create -f nginx/nginx-service.yaml

# 创建 tomcat 资源
kubectl create -f tomcat/tomcat-deployment.yaml
kubectl create -f tomcat/tomcat-service.yaml

# 销毁 nginx 资源
kubectl delete -f nginx/nginx-deployment.yaml
kubectl delete -f nginx/nginx-service.yaml

# 销毁 tomcat 资源
kubectl delete -f tomcat/tomcat-deployment.yaml
kubectl delete -f tomcat/tomcat-service.yaml
```
