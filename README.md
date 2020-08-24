# helloworld-app

**How to use:**

- Dockerfile will be automatically built using Dockerhub builds based on the war file in [app](./app)
- Each tag (with the right naming convention e.g: 0.0.1) will create a docker tag with each push to master building latest tag
- To update the docker image in the apps chart change [here](https://github.com/shayharush/helloworld-app/blob/master/charts/helloworld/Chart.yaml#L21)
- use `helm install [name] ./charts/helloworld`
