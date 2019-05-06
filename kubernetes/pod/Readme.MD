kubectl apply -f pod.yaml
kubectl get po | grep myapp
kubectl logs myapp
kubectl describe pod myapp

cleanup:
kubectl delete -f pod.yaml