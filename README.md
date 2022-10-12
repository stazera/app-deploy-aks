
once the deployment and service are applied, you need to port forward to test locally on minikube
k port-forward svc/angular-service 8040:8080
 
and then test:
http://localhost:8040/