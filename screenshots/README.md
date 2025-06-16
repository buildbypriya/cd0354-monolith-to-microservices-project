# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed - attached


* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook) - not attached
* Travis CI showing a successful build and deploy job - not attacheds
I could not attached travis ci as they have currently disabled free trial. I tried connecting with the team, in case I can get access to free trial for a while but they have denied. I have attached the screenshot for the same.
I have created .travis.yml in the project root but could not use it to push the image. So I have manually pushed the image and attached dockerhub respository screenshot


## Kubernetes - attached
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```

