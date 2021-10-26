# wordpress_and_mysql_on_replicaset
Deploying WordPress and MySQL with Persistent Volumes and LB on Kubernetes ReplicaSet

  * wordpress-replicaset.yaml 
1. Service
2. PersistentVolumeClaim
3. Replicaset

  * mysql-replicaset.yaml
1. Service
2. PersistentVolumeClaim
3. Replicaset

 * kustomization.yaml
 1. secretGenerator
 2. mysql-password
 3. wordpress and mysql resources

# To run both applications simply do:
* kubectl apply -k ./
# To delete everything 
* kubectl delete -k ./
