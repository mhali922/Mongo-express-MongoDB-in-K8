This is a CI/CD pipelines wherein I'm deploying mongo-db and mongo-express deployment in Kubernetes cluster.



I have written 4 yaml files to deploy -

1.) Deployed secrets - mongo-secrets.yaml

2.) Deployed mongo-DB deployment and service  - mongo.yaml

3.) Deployed the Mongo-express ConfigMap yaml file - mongo-configmap.yaml

4.) Deployment and Service for the mongo-express  - mongo-express.yaml

I need to ingress controller in order to remove Node-port.
