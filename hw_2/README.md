# Installation
1. Add common bitnami repo:
`helm repo add bitnami https://charts.bitnami.com/bitnami`
2. Install postgresql:
`helm install pgsql bitnami/postgresql -f ./pgsql/values.yaml`
3. Install simple-crud application:
`helm install simple-crud ./simple-crud`