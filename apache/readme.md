#to access the pod

#https://servicename.namespace.svc.cluster.local
#https://apache-service.apache.svc.cluster.local


kubectl run -i --tty load-generator --rm --image=busybox:1.28 --restart=Never -- /bin/sh
