# k8_blue_green

kubernetes Blue/Green Deployment example


Created 'Blue' and 'Green' deployments using the following yml file: bluegreen_deployment.yml

Created NodePort service pointing to deployment: bluegreen_service.yml

Change 'selector: app:' section in bluegreen_service.yml to point it to either 'app: green' or 'app: blue' label.

example:
1. selector: app: green
2. selector: app: blue


