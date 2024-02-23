# helm-cloudbeaver
A simple repo with the Helm Chart for deploying Cloudbeaver.

## Build & update charts 

If you want to build and update chart that are in this directory. 

1. go to chart directory
2. after updating version in Chart.yaml run `helm package .`
3. mv tgz to root 
4. run `helm repo index .`
5. push to `main` branch to publish the new chart version