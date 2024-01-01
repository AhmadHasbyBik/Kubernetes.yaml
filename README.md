*KUBERNETES* <br>
minikube start <br>
kubectl get node //check node <br>
kubectl create -f nginx.yaml //create pod <br>
kubectl get pod //check pod <br>
kubectl get pod --show-labels //check pod with label <br>
kubectl describe pod <br>
kubectl delete pod namepod <br>
kubectl port-forward nginx-probe 8080:80
