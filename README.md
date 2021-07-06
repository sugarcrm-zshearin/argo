

Followed tutorial here: https://argo-cd.readthedocs.io/en/stable/getting_started/

I copied manifest to this directly instead of using yaml specified in getting started article.

Was relatively simple, but did have to use the following command to enable loadbalancer service type in minikube env:
`minikube tunnel`  (see link here: https://stackoverflow.com/questions/44110876/kubernetes-service-external-ip-pending)
