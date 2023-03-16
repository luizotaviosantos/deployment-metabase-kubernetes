![metabase-setup-diagram](https://user-images.githubusercontent.com/95440965/225619296-aa0988a1-58d8-4e44-b992-8fb37bb85b71.png)

# INTRODUCTION
<h3>
This repository was created to help you deploy Metabase on a Kubernetes cluster for large-scale use and scalability using a yaml deployment. The deployment consists of a YAML file containing 5 objects: Namespace, ConfigMap, Deployment, Service and Ingress. This allows you to connect Metabase to an external database. The repo also includes a PostgreSQL YAML file in case you want to deploy a database in your kubernetes cluster.<h3>

# BRIEF
<h3>
Metabase's yaml file consists in 5 objects:

1.  Namespace (Creates 'metabase' namespace)
2.	ConfigMap (Environment variables for conection on).
3.	Deployment (Deployment with v0.44.2 image).
4.	Service (Service running on tcp 3000).
5.	Ingress (Ingress for external access for tcp port 3000..).
<h3>


# BUILD AND DEPLOY
<h3>After the deployment, wait until the creation and preparation of the database is complete.<h3>


# TROUBLESHOOTING
<h3>Check the metabase pod logs for troubleshooting.<h3>
