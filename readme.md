# Deploy
kubectl apply -f config.yaml -f postgres.yaml -f initdb.yaml -f deployment.yaml -f service.yaml -f ingress.yaml