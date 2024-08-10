This project demos very basis componenents of Kubernates

mongo-config.yaml
mongo-secret.yaml
mongo.yaml
webapp.yaml

**K8s commands**

Command to start the minikube - it creats a cluster
**_minikube start_**

Create the K8 components - ConfigFile, Secret, Deployment and Services
**_kubectl apply -f <<file_name>>_**

After successful creation of K8 components, check the pods status
**_kubectl get pods_**

Get minikube node's ip address
**_minikiube IP_**

Access the application in the server
**_http://<ip_address>:30100_**
