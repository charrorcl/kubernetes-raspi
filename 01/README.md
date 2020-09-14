
## ENABLE - Microk8s Ingres

	$ microk8s enable ingress

## APPLY - YAML Deployment, Services(ClusterIP), Ingress(Backend - Selector[app:hello, app:hellov2])

	$ microk8s kubectl apply -f .
