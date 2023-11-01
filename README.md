# NGINX
To install nginx, make sure that helm ins installed
Create a namespace nginx
 helm repo add https://helm.nginx.com/stable
 helm repo update
 helm search repo nginx-ingress     
 helm install  nginx    nginx/nginx-ingress -n nginx  
