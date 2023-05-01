# Voting-APP
Voting app kubernetes project

Create deployments and services for Redis, Postgres, Voting app and Result app in your k8s cluster.
<pre>kubectl create -f xxx-deployment.yaml
kubectl create -f xxx-service.yaml</pre>

Then create deployment for Worker app.
<pre>kubectl create -f worker-app-deployment.yaml</pre>
