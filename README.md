# kubernetes
Kubernetes test projects

-1 create helm chart

-2 Create values.yaml Firs

-3 config wordpress-deployment.yaml

-4 config mysql-deployment.yaml

-5 config phpmyadmin-deployment.yaml

-6 config ingress.yaml

-7 in helm chart directory use this command for Package the Helm chart: "helm package wordpress-site"
This command will create a .tgz file.

-8 Now, you can install the Helm chart with: "helm install wordpress-site ./wordpress-site-1.0.0.tgz"

-9 check the status of the resources with: kubectl get pods -A
