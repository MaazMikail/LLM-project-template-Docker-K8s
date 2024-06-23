'''

pip install "fastapi[all]"
uvicorn main:app --reload

{
  "text": "Who is the hero of the story? "
}

docker build -t chagpt-project . 
sudo docker build . -t chatgpt-project:1 

sudo docker run -d -p 8000:8000 chatgpt-project:1



kubectl get pods
kubectl apply -f pod.yaml
kubectl describe pod myapp
kubectl apply -f svc-local.yaml
kubectl get svc
kubectl delete pods --all
kubectl delete svc --all
kubectl delete --all deployments
kubectl api-resources

# deployment object - encapsulate pods
- self healing
- scaling
- rolling updates
- load balancer as well

# Deployment controller
- checks that all deployment objects are running

# secret creation
kubectl create secret generic openai-secret --from-literal=API_KEY=<api_key>

'''