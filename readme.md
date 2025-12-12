# deploy a k3s node with faas
## get openfaas password
### kubectl  get  secret  -n  openfaas  basic-auth  -o  jsonpath="{.data.basic-auth-password}"  |  base64  --decode;  echo