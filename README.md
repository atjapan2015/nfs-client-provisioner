helm install nfs-client-provisioner --name mysc --namespace public-service --set nfs.server=k8s-master --set nfs.path=/k8sdata --set imagePullPolicy=IfNotPresent
