To use this demo, execute the following commands:

`make undeploy docker-build kind deploy sample`


To inspect the environment variables on the pod, use 

`kubectl exec nginx-sample-<TABCOMPLETE> -- printenv`

