Set secret key in kubernetes before creating the mssql

kubectl create secret generic mssql --from-literal=SA_PASSWORD="password@1" -n psnamespace



Create ingress controller
Go to https://kubernetes.github.io/ingress-nginx/deploy/
select Docker Desktop option

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.0.4/deploy/static/provider/cloud/deploy.yaml

