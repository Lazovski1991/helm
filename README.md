# helm
1. Add remote repository:

    `helm repo add my-repo https://lazovski1991.github.io/helm-repo/`

2. Update repository 
   
   `helm repo update`

3. Install chart

   `helm install front-service my-repo/spring-application`

   `helm install front-service my-repo/spring-application --values ./values.yaml`
4. Uninstall chart

    `helm uninstall front-service`