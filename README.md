# kubernetes
Kubernetes test projects

# Create values.yaml First

# You can install the Helm chart with the following commands:

helm repo add bitnami https://charts.bitnami.com/bitnami

helm install my-mysql -f values.yaml bitnami/mysql

helm install my-wordpress -f values.yaml bitnami/wordpress

helm install my-nginx -f values.yaml bitnami/nginx-ingress-controller

helm install my-phpmyadmin -f values.yaml bitnami/phpmyadmin

